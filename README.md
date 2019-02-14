# Cybertrust

Due to the unique nature of this capstone project, the actual codebase will not be included within this repo, only the supporting documentation would be included.

* [Project Bid PDF](/ProjectBid.pdf)
* [Project Bid](/ProjectBid.md)

## Milestone 1

* [Project Milestone 1](/CYBR4580-8950/Project-Milestone-1.md)

## CYBR4580/8950 Project Milestone 1:
Requirements analysis and planning (Project Proposal Stage)

### Executive Project Summary
This project will supplement the current CyberTrust web application by providing additional user and administrative tool sets.  The goal of CyberTrust is to provide a research platform for exploring the phycology of phishing from a user's perspective.  Currently, it is designed to identify what a user identifies as a trusting vs threatening form of communication.  The obtained research data is then used to help define effective training to prevent the user from becoming a victim.  Currently CyberTrust does not segment the user base, nor does it provide a comprehensive mechanism for delivering complex reports.  The proposed changes will segment the user group into common users and administrative users.  The addition of robust administrative reporting tools will provide an interface for gathering and compiling critical reports, accessed through one convenient user interface.  The common users will be provided with a user statistic screen to supply them with reports, related directly to his/her activities, aimed to supplement training by providing relative statistics of personal usage.  

Project Goals:
- Segment the user base into Administrative and User groups to allow separated functionalities.
- Provide an administrator screen which fill provide a consolidated toolset for creating reports.
- Create a user statistics screen to display analytics relating to individual usage.

Once completed this will increase the effectiveness of the CyberTrust research platform by providing detailed information to researchers, business, and users.  These reports will facilitate researchers and businesses with tools needed to aggregate information into useful statistics.  These statistics are needed to better identify traits within a variety of communications that present increased risk to user victimization.  In addition, displaying personal user statistics will provide an intimate connection for individual risk factors.  This will likely provide a deeper meaning when implementing a training strategy.   


### Proposed project timeline

![Gant chart](/CYBR4580-8950/SupDocs/GantChart.png "Gant Chart")

The project will follow the following proposed timeline following the three project milestones. The first project milestone is the completion of this set up. Project milestone 2 is expected to complete 3/26/2019 with the development of a concept presentation. Project milestone 3 will conclude May with the projects final presentation.

The project timeline will be modified as needed and is located at this location:
* [Gant Chart](/CYBR4580-8950/SupDocs/CybertrustGantChart.xlsx)

### Risk list
![Risk Matrix](/CYBR4580-8950/SupDocs/RiskMatrix.png "Risk Matrix")

* This risk matrix describes what threats to the project exist, the likelihood that these threats pose and what mitigations exist to minimize these threats.

|Risk name| Value (Rating)     | Impact     | Likelihood | Description | Mitigation |
|-------------------|------------|------------|------------|-------------|-------------|
|Meeting / Scheduling conflict | 5 (Medium) | 3 (Minor)| 9 (Very Likely)| Each member has a busy lifestyle and will need to find time to coordinate requirements to the project with each members. | Team members will utilize Slack, GitHub and email to coordinate information with each other. |
|Project Member leaves or reassigned | 8 (Medium High)| 10 (Severe) | 3 (Unlikely) | The loss of a team member will force other members to increase the workload to other members of the team. | Tasks will be assigned utilizing the GitHub Kanban board system. |
|Unable to learn EmberJS | 4 (Low Medium) | 6 (Moderate) | 2 (Very Unlikely) | No members of the team are able to understand or generate appropriate Ember JS code. | Ember JS has multiple resources to learn the code to be learned by members who don't know the codebase. |
|Failure to Complete Tasks in Scheduled Time | 4 (Low Medium) | 5 (Moderate)| 4 (Unlikely)| Each task has a scheduled time that it should be complete by in order to keep the project on time. | Team members assist others, if needed, with tasks that are behind schedule. Can push the timeline to complete the task if needed. |
|Design is infeasible | 6 (Medium) | 8 (Significant)| 2 (Very Unlikely)| The design of our addition to the project is overly costly or can't support the requirements | Team members will work together to be sure each feature will work with the proper design without increasing the cost immensely. |
|UI is bad quality | 5 (Low Medium) | 6 (Moderate)| 4 (Unlikely)| The UI is buggy, difficult to use, or doesn't allow tasks to be completed. | Team members will focus on testing, finding, and fixing bugs that flaw the UI. |

### Project Methodology
![Use Case "User"](/CYBR4580-8950/SupDocs/UseCase.png "Use Case User")

![Use Case "Admin"](/CYBR4580-8950/SupDocs/UseCaseadmin.png "Use Case Admin")

![Misuser](/CYBR4580-8950/SupDocs/Misuser.png "Misuser")

### Mockup Design
![System Diagram](/CYBR4580-8950/SupDocs/SysDiagram.png "System Diagram")

![Login](/CYBR4580-8950/SupDocs/MockupLogin.png "Login")

![User Portal](/CYBR4580-8950/SupDocs/MockupUserPortal.png "User Portal")

### Resources Needed
- Node.js
- Ember and Ember-cli
- Console
- IDE /Code Editors
- Docker
- Browser and Addons

## Development Framework
- Ember.js
- Django / Python
- PostgreSQL

|Resource  | Dr. Hale needed? | Investigating Team member | Description |
|-------------------|---------|---------------------------|-------------|
|Node.js| Yes | Fadila | Install NPM which is dependency to install ember and other node packages |
|Ember and Ember-cli| Yes | Team | Generate and manage our app components, structure and download ember addons |
|Console| Yes | Fadila | This will make serving out app faster |
|IDE/ Code Editors| Yes | Fadila | SublimeText, Atoms and few more IDE will help speed development time   |
|Docker| Yes | Fadila | Create/Manage/Destroy our local environment and all of the required dependencies |
|Browser and Addons | Yes | Fadila | Chrome Developer tool and Ember inspector will help troubleshooting the application  |
|Bower| Yes | Fadila | Will be used for ember package manager  |

## Resource and Technology Install
- IDE
	- Sublime Text
	- Visual Studio Code
	- Atom
	- IntelliJ
	- WebStorm

- Browser and addons
	- Google Chrome developer tool
	- Ember Inspector
		- http://bit.ly/ember-inspector

- Node.js Install
	- Mac Install
		- Using Homebrew
			- http://brew.sh
			- `brew install node`
	- Windows Install
		- Using chocolatey
			- https://chocolatey.org
			- `choco install node.js .install`
- Console
  - Mac
    - iterm
      - https://www/iterm2.com
  - Windows
    - PowerShell console

- Ember-cli
	- Run:
		- `npm install -g ember-cli@latest`
		- `npm install -g bower`

- Docker
	- https://docs.docker.com/install/


### First Sprint Plan
![Sprint Plan](/CYBR4580-8950/SupDocs/sprintplan.png "Sprint Plan")
* [Sprint Plan](https://github.com/mgalde/Cybertrust_Admin#workspaces/)


The team will follow a 2 week sprint planning cycle and will utilize ZenHub as the resource to manage this piece of the project.
* [ZenHub](https://chrome.google.com/webstore/detail/zenhub-for-github/ogcgkffhplmphkaahpmffcafajaocjbd?hl=en-US)
