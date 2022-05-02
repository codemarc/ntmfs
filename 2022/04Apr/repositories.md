---
marp: false
author: Marc J. Greenberg
size: 4:3
theme: gaia
paginate: true
backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

# Par Tech Source Repositories

A repository location represents the official system of record for a particular product. A system of record is the location where the artifacts of work product are stored. Work product refers to documents, notes, images, source code, theories, scripts, spreadsheets, etc. Artifacts are created or collected by product, development, and sometime business stake holders. All work product MUST BE sourced in an official system of record.

Bringing together systems of record means that decisions based on the current state of the source code can bring in a range of supporting facts that can make those decisions stronger. 

At Par Tech  there are several types of repositories:

## Document Stores

SharePoint  
One Drive,  
Google Drive,  
Confluence, 

## Version Control Systems
GitHub  
Azure Devops - Git In Visual Studio Team Services
Bitbucket on prem (AWS)

---
 
  Source Systems of Record by Project:

  | Brand  | Product               | Project              | Repository | Type      | Content 
  | ------ | ----------------------| ---------- | --------- | ----------------------------------- |
  | Brink  | API Platform Services | [AccountsService]



  | --------- | ------------------| ---------- | --------- | ----------------------------------- |
  | API Platform Services | [AccountsService] | [APIP]     | Bitbucket | API Platform Services and Data                                                            


---

  | [Brink][1]              | Bitbucket | [Default Team]     | TFVC | our main web site - \$/Default/Web/Main/V2                           |
[APIP]:    https://devops.partech.com/bitbucket/projects/APIP
[AccountsService]: https://devops.partech.com/bitbucket/projects/APIP/repos/banzai.accountsservice/browse

Name	Key	Description
Banzai Repositories
Banzai Repositories	APIP	Team Banzai Repositories

Brink
Brink	BRIN	
BrinkAboveStore
BrinkAboveStore	BAS	Project for new Above Store services
Brink Archive
Brink Archive	BA	Home for defunct Brink repos that we're not quite comfortable deleting yet.
BrinkQA
BrinkQA	BRQA	Brink QA Project
CLOUD
CLOUD	CLOUD	
DigitalOrderManager
DigitalOrderManager	DIG	
iSivaProjects
iSivaProjects	ISIVA	
PixelPointPOS
PixelPointPOS	PIX	
Platform Console
Platform Console	PCON	Platform Console
Slack Chat Bots
Slack Chat Bots	SCB	
Test
Test	TEST	Stash test project
Utilities
Utilities




  | [Buildinglink Default]  | [Default Team]     | TFVC | our legacy repository on TFS                                         |
  | [Buildinglink Vue Apis] | Gonzolo            | TFVC | vue api implementation versions                                      |
  | [Vue-Architecture]      | [Vue Team]         | Git  | repo contains the main Vue project code                              |
  | [BlobHandler]           | Joe                | Git  | repo for azure func app blob handling /thumbnail sizer               |
  | [Data-Models-Admin]     | Oleg               | Git  | developer tool to create mastered model data                         |
  | [Data-Models-Generator] | Gonzolo, Orry, Ben | Git  | Simon's tool, (db + rules to generate odata style api from ef models |



  [1]: https://devops.partech.com/bitbucket/projects/BRIN