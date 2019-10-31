# BGSE DSC classification data
Barcelona, 17 Sep 2019

## Summary
The aim of this template is to standarize the folder structure and main contens of all consulting projects.

In following points we describe briefly the minimum contens of each folder, that should be populated as the project evolves and the contens are made available. By the end of the project, all folders should be populated convieniently.
Depending of the non-disclosure agreement, Data folder may be cleaned by the end of the project, together with sensible information.

Subfolder creation is free under this structure, but try to minimize if possible.
Other folders can be created, but should be temporary, and to be removed by the end of the project.

##01_ProjectMgmt
Here we store main files that define the project, namely:
+ Contract
+ Business case documentation (if available)
+ Technical specifications (if not included in contract)
+ Project plan (with scope, milestones, etc), if not included in previous
+ Project control tool: May be a link to an online tool (Trello, Slack, etc)

##02_MOM
Minutes of meetings, following the structure and file naming of the sample one.

##03_Data
Repository of data and metadata, here we distinguish:
+Raw: Exactly as received from the client.
+Processed: After ETL and processing by DSC (e.g. outliers removed, filling, creating/ features, etc)
+Output: Results of the analytics project that solve the problem/project statement for a particular dataset

Here, metadata file(s) explaining the data are highly recommended for all folders.
If needed, maybe simply a link to a cloud storage.

##04_Code
Generally, a link to the GIT repository is enough as long as it exists.
Anyways, the sample structure for Code folder can be found at:
where we should have our repository. We can clone the GIT repository into this folder

##05_Deliverables
Here we save what we sent to the client as deliverables, according to the project plan.
One should be able to distinguish between intermediate deliverables and the final deliverable.

##06_Credential
This helps explaining to any audience what we did in the project. At minimum we should have two credentials that have to be ANONIMYZED (no client logos or names, no sensible data):
+OneSlider deck: explaining briefly the 'business case', the methodological highlights and the main results showing the value of our project. This can be published in our website;
+ProjectSummary deck: Max 20 slides with an initial 'Executive summary' slide, followed by sections explaining 1)the case (business problem, data, constraints) 2) The solution (methodology, architechture) 3) Results (showing VALUE and showing that we solve case) 4) Next steps (optional, if any further development or implementation is delayed to a posterior project) . To be presented to any audience (included non-technical) in 15-20'

Nice to have:
+TechnicalDeck: Technical details deck of the solution, to be presented to data scientists. Ideally also with main take aways (main pain points, ideas for future, etc)
+Demo: If there is a life demo (i.e. dashboard), please save if here or place the corresponding link to the online demo. If so, add a slide in the Project Summary deck that links the presentation to the Demo (if can be a simple snapshot). If needed, add a small document with instructions to run the demo
+DemoVideo: If we want to excel, record a video of a life presentation of project+demo. Maybe very useful to boost the project impact or to show anywhere.

