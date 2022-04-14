---
marp: true
author: Marc J. Greenberg
size: 4:3
theme: gaia
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---
<style>
  section {
   font-family: 'Roboto', 'Segoe UI', 'Liberation Sans', 'Helvetica', 'Arial', sans-serif;}
  h1 {font-size:26pt;}
  h2 {font-size:22pt;}  
  h3 {font-size:20pt;}
  h4 {font-size:16pt;}
  h5 {font-size:10pt;}
  p,li {font-size:14pt;}
  footer {font-size:14pt;text-indent:48px}
</style>

# Notes to my future self V3, 
### [_public edition_][swyx] by [Marc J. <span style="color:darkgreen;">Green</span>berg](mailto:marc@codemarc.net) (marc@codemarc.net)

<br/>

NTMFS is essentially a blog. As once explained by the architect in the [matrix reloaded][redux] this is not the first version of NTMFS.  

#### [Robot Monkey Butler][rmb]

This time It will take on a presentation wiki flavor where each topic can be thought of as a presentable subject. As I document my discoveries and share them in prose, I expect to create a [learning in public][swyx] environment. I am very exciting ( ͡° ͜ʖ ͡°) to get started.

Additionally this work is essentially about building evolutionary architectural thought framing around technological developments. It is expected to often morph and occasionally pivot and we iterate and evolve our understanding of things

<footer>See: the <a href="#tools">tools we use</a></footer>

<!-- References -->
[swyx]: https://www.swyx.io/learn-in-public/
[rmb]: https://fb.watch/9P1cHyeIXJ/
[redux]: https://youtu.be/LN8EE5JxSGQ?t=86

---

# April 2022

| Sun | Mon | Tue | Wed | Thu | Fri | Sat |
| --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     | 01  | 02  |
| 03  | 04  | 05  | 06  | 07  | 08  | 09  |
| 10  | 11  | 12  | [13]| 14  | 15  | 16  |
| 17  | 18  | 19  | 20  | 21  | 22  | 23  |
| 24  | 25  | 26  | 27  | 28  | 29  | 30  |

  
##### 3/13 [restart/reboot/redux][13]


<!-- References -->
[13]: #20220413

---

### Tools used with NTMFS <a id="tools">

- [Marp][t1] - Markdown Presentation Ecosystem
- [Mermaid][t4]- Generation of diagrams and flowcharts from text in a similar manner as markdown.
- [Visual Studio Code][t0] with plugins: [Marp for VS Code][t2], [Mermaid+Draw.io][t3]

<footer><b>Note: </b>./.vscode/extensions.json lists recommended plugins for NTMFS

<!-- References -->
[t0]: https://code.visualstudio.com/
[t1]: https://marp.app/
[t2]: https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode,
[t3]: https://marketplace.visualstudio.com/items?itemName=nopeslide.vscode-drawio-plugin-mermaid
[t4]: https://unpkg.com/mermaid@0.5.2/exdoc/index.html

---
<style>
h4 {font-size:11pt;font-style:italic;margin-top:-3px}
p {font-size:11pt;margin-bottom:12px;}
</style>


### <a id="20220413">Restart / Reboot / Redux </a>
#### Wed April 13th, 2022 09:00am ET

Its been a while since I posted an NTMFS entry and I am not sure why that is. Maybe because I am busy with my new job mapping out my onboarding journey at [Par Tech][pt1]. As a newbie navigating the waters of a new organization I have decided keep a completely open mind about all things **par** and **tech** and I attempt to join the party. 

There is so much I have learned in the last week, some of which is recorded my writing journal, some in slack, some from confluence and some from direct conversations with specific individuals that were listed in my meet and learn document supplied out CTO. Perhaps I need to say my role is the chief of staff in the office of the CTO (Octo), as such it make sense to reach out and actually meet the staff. 


Before you ask, of course I created my chrome extension holding the links I discovered. This one is called parlinks, and you can contact me at marc_greenberg@partech.com to request access.

![width:640px](./img/parlinks.png)

<!-- References -->
[pt1]: https://www.partech.com/

---

<style scoped>
  h4 {font-size:11pt;font-style:italic;margin-top:-3px}
  p {font-size:11pt;margin-bottom:12px;}
  ol,li {font-size:11pt;}
  hr {margin-top:40px}
</style>

### Branching Strategy
#### Wed April 13th, 2022 12:00 ET

Sat thru an interesting conversation on git branching strategy. It is sad to see the same topics that have been under discussion in every software company over the past 5 years are still under discussion. Good conclusion reached today. 

#### Action Items:  

1. Switch to a pure trunk based branching strategy.
2. Remove wildcard package version references. (maybe enforce this by policy).
3. Document the actual flow and policies.

<hr/>

### Cheers Governor 
#### Wed April 13th, 2022 02:00 PM ET

A few days ago Steve and I began a discussion on the concept of governance, guardrails and guiderails with respect to major technology choices (software, frameworks, databases, etc) across Par.

![width:300px](./img/ggg.png)

---
### Cheers Governor (continued) 
#### Wed April 13th, 2022 02:00 PM ET

I have been spelunking thru the punchdev instance of confluence and I found a name associated with lots of architectural content: Who is  andrew berry?

Well it turns out that andrew was an architect from Australia, working with Guarish Sharma who wrote a good number of process documentation. 

* [Preferred Patterns and Platforms][P1]
* [Architecture Pattern Glossary][P2]
* [Software Architecture][P3]
* [Platform Architecture][P4]
* [Integration Architecture][P5]


<!-- References -->
[P1]: https://punchhdev.atlassian.net/wiki/spaces/ENGINEERIN/pages/91914332/Preferred+Patterns+and+Platforms
[P2]: https://punchhdev.atlassian.net/wiki/spaces/ENGINEERIN/pages/80838716/Architecture+Pattern+Glossary
[P3]: https://punchhdev.atlassian.net/wiki/spaces/ENGINEERIN/pages/58622860/Software+Architecture
[P4]: https://punchhdev.atlassian.net/wiki/spaces/ENGINEERIN/pages/58589889/Platform+Architecture
[P5]: https://punchhdev.atlassian.net/wiki/spaces/ENGINEERIN/pages/59179024/Integration+Architecture

<!-- ---

### Building Punchh Server Redux
#### Wed April 13th, 2022 04:00 PM ET

Even though I have already built the Punchh server once, I am ready to try this again. This time I am specifically looking at tools and tech choices.

Pages to consider:
* [How to get access to Tools](https://punchhdev.atlassian.net/wiki/spaces/DEVOPS/pages/1671234973/How+to+get+access+to+Tools)
 -->

<!-- 
Guarish Sharma was kind enought to share this 

These items are from [punchdev confluence][pc1].

* From [Day 1 Checklist](https://punchhdev.atlassian.net/wiki/spaces/ENGINEERIN/pages/106627582/Day+1+Checklist)
 -->

<!-- References -->
[pconf]: https://punchhdev.atlassian.net/wiki/spaces/
[pc1]: https://punchhdev.atlassian.net/wiki/spaces/ENGINEERIN/pages/25854055/Engineering+On-boarding+work+in+progress
