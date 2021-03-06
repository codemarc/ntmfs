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

# May 2022

| Sun | Mon  | Tue  | Wed  | Thu  | Fri | Sat |
| --- | ---  | ---  | ---  | ---  | --- | --- |
| 01  | [02] | [03] | [04] | [05] | 06  | 07  |
| 08  | 09   | 10   | 11   | 12   | 13  | 14  |
| 15  | 16   | 17   | 18   | 19   | 20  | 21  |
| 22  | 23   | 24   | 25   | 26   | 27  | 28  |
| 29  | 30   | 31   |      |      |     |     |


##### 5/02 [my month 2][02]
##### 5/03 [pig and chicken][03]
##### 5/04 [bacon and eggs][04]
##### 5/05 [rome realized][05]ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ[Go back to April](./2022/04Apr/README.md)

<!-- References -->
[02]: #20220502
[03]: #20220503
[04]: #20220504
[05]: #20220505

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


### <a id="20220502">Month Two, stay focused, renew, redux </a>
#### Mon May 02nd, 2022 09:00am ET

It is been a month since I started at Par Tech. and I now have put a little rubber on the road. I have met many really nice and smart people. Some important items I am working on include:

* [From a Par Perspective, create a shared architectural vision][4]
  * Break the silos 
  * Create a core/cross company architectural review team.
  * Use the review process for UCP use cases as to build a shared understanding the strategic roadmap.


* [Meet / Understand the Staff][2].

* [Move the Source System Of Record agenda forward][3]

---
###  [Par-links v0.0.6 - Quicker Turnarounds][5]
#### Mon May 2nd, 2022 09:00am ET

As of v0.0.6 of Par Links (My chrome extension) I have enabled a split scheme on where menu data comes from. There are now 2 github projects that comprise par-links.

https://github.com/par-brink/par-links contains the source build and publishing content of the project and the default menu data for this version. https://github.com/codemarc/par-links-data.git contains the updates to the menu in between releases. To load the most recent updates you press the refresh icon and the file https://github.com/codemarc/par-links-data/blob/master/default.json will be loaded as the menu data.
![width:340px](./img/RefreshData.png)

You can tell it is loaded by the plus + indicator following the version number. Press the screen icon to revert to the release level meant.

![width:340px](./img/RevertData.png)

---

### <a id="20220503">Which way to the Lab?</a>
#### Tue May 3rd, 2022 10:00am ET


Ever since I first heard the scrum, pig and chicken story I have always wanted to open a breakfast joint named Bacon and Eggs (scrumbut intended). The original story goes like this...  
<br/>

![width:600][6]  


<br/><br/>As a brink integrator, I take it for granted that everyone has access to real data. In reality, its not true. Developers here setup their private environments and do not really share. They generate faux data to make sure the system is working. I wonder if I can use my integrator lab environment. And can I set it up to be used as a research / demo platform for UCP?

---

<style scoped>
  h5 {margin-left:280px;margin-top:-12px}
</style>

### <a id="20220504">Bacon and Eggs</a>

#### Wed May 4th, 2022 7:00am ET


![width:460px](./img/BaconAndEggs.png)
##### Another fine ucp venue


#### First thoughts...

* As a thinker I need an experimental environment where I can flush out answers to proposed designs.
* will need a brink pos, data central, and punchh loyalty account setup. 

---

<style scoped>
  h6 {margin-top:24px;margin-bottom:0;font-size:16pt;}
</style>

### <a id="20220505">Team Rome</a>

#### Wed May 5th, 2022 7:00am ET

_There was a dream that was Rome. It shall be realized._

Trust is the number one priority at Partech. The architects on team (Rome) set the standards for engineering excellence across the Par ecosystem. They work on assuring alignment between our technology and strategic business goals. This matrixed group contributes to the definition and implementation of the long-term company-wide technology roadmap focused on architecture, platform, and data design. 

###### Guiding Principles

* EMPOWER OTHERS
  Mentor / Collaborate across all development and product teams. Break the Silos!

* DRAW THE OWL
  Lead and guide teams in determining the appropriate technologies, structuring of data, and workflows in support of high scale distributed systems. Figure it out, Ship It and Iterate

* DON’T SETTLE
  Partner with other Architects and stakeholders to ensure all technology solutions align with product, security, and architecture long term vision and roadmap. Win Together

* BE AN OWNER
  Ensure the successful delivery of projects from vision, through execution, and reliable, dependable, scalable, operations. 


<!-- References -->


[6]: https://i0.wp.com/helpingimprove.com/wp-content/uploads/2021/01/agile-safari-pig-and-chicken-part1-1024x398-1.png?resize=625%2C244&ssl=1

[5]: https://chrome.google.com/webstore/detail/parlinks/dcdlniniklogobinjapppmaeafneiddl

[4]: https://partech-my.sharepoint.com/:p:/p/marc_greenberg/Efgo2gaQQjVKrjpDzAbjd6gB8UAU9q-paP4O9T3oyyIXOw?e=0tMlV2

[3]: repositories.md

[2]: https://partech-my.sharepoint.com/:x:/r/personal/steven_berkovitz_partech_com/_layouts/15/Doc.aspx?sourcedoc=%7BEECA7908-905F-40B9-9158-941B04D59787%7D&file=Onboarding%20Plan%20-%20Marc%20Greenberg.xlsx&action=default&mobileredirect=true

[1]: https://partech-my.sharepoint.com/:b:/p/marc_greenberg/ERUl2KnfIo1Or_NnjLyF0QAB53mTcIVS5RdPiEKJD8vABg?e=A9gxPm
