# Cybertrust

Due to the unique nature of this capstone project, the actual codebase will not be included within this repo, only the supporting documentation would be included.

* [Project Bid PDF](/ProjectBid.pdf)
* [Project Bid](/ProjectBid.md)

## Milestone 1

* [Project Milestone 1](/CYBR4580-8950/Project-Milestone-1.md)
* [Project Milestone 2](/CYBR4580-8950/Project-Milestone-2.md)

## CYBR4580/8950 Project Milestone 1:
Requirements analysis and planning (Project Proposal Stage)

### Executive Project Summary
This project will supplement the current CyberTrust web application by providing additional user and administrative tools.  The goal of CyberTrust is to provide a research platform for exploring the psychology of phishing from a user's perspective.  Currently, it is designed to identify what a user identifies as a trusting or threatening form of communication.  The obtained research data is used to help define effective training to prevent the user from further victimization.  Currently, CyberTrust does not segment the user base, nor does it provide a comprehensive mechanism for delivering complex reports.  The proposed changes will segment the user group into common users and administrative users.  The addition of robust administrative reporting tools will provide an interface for gathering and compiling critical reports, accessed through one convenient user interface.  The common users will be provided with a user statistic screen to supply them with reports, related directly to his/her activities, aimed to supplement training by providing relative statistics of personal usage.  

Project Goals:
- Segment the user base into Administrative and User groups to allow separated functionalities.
- Provide an administrator screen which fill provide a consolidated toolset for creating reports.
- Create a user statistics screen to display analytics relating to individual usage.

Once completed this will increase the effectiveness of the CyberTrust research platform by providing detailed information to researchers, business, and users.  These reports will provide researchers and businesses with tools needed to aggregate information into useful statistics.  These statistics are needed to better identify traits within a variety of communications that present increased risk to user victimization.  In addition, displaying personal user statistics will facilitate an intimate connection for individual risk factors.  This will likely provide a deeper meaning when implementing a training strategy.   


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

## Milestone 2

* [Project Milestone 2](/CYBR4580-8950/Project-Milestone-2.md)
# Milestone 2 Progress Report (28 March 2019)
## Overview
The Cybertrust team has worked on the dashboard page within the cybertrust project. The team has suscessfully been able to poll backend user data to publish into the frontend to show the cybertrust admin user useful data about the test subjects in a meaningful way.

## Outcomes
* We have been able to identify what individuals are ranked as low risk, mederate risk and high risk based on how the user took the test.
* We have been able to identify and represent false negitive and true positive vs true negitive and false positive to the user based on questions / experiments so that the end user can make useful determinations about the data.
* We have also been able to display the top 5 low performers and display their progress on the user screen so that the cybertrust administrator can take action if needed to ensure members complete the exercise.
* We have been able to generate new page views without loading a new page so that the user can review information from a single view

## Hinderances
* Ember charts utilized backend data which did not play nicely with the calculations we wished to preform. The team moved to zingcharts which added a extra step for set up. This setup caused a delay so we reverted back to the ember chart view. For visualization purposes we will likely move back to zing chart and resolve the issues.
* The team has moved into two teams, one visualization and the other backend data. This has improved productivity but buth teams need to communicate so that the process moves faster. We are on a schedule which is being met but the complexity between the two groups makes this slow moving.
* Team is still trying to find best way to display False Negitive and True Positive vs. True negitive vs. False positive to the end user in a useful way to the end user.

## Ongoing Risks
### Risk list
![Risk Matrix](/CYBR4580-8950/SupDocs/RiskMatrix.png "Risk Matrix")

* This risk matrix describes what threats to the project exist, the likelihood that these threats pose and what mitigations exist to minimize these threats.

|Risk name| Value (Rating)     | Impact     | Likelihood | Description | Mitigation |
|-------------------|------------|------------|------------|-------------|-------------|
|Meeting / Scheduling conflict | 5 (Medium) | 3 (Minor)| 9 (Very Likely)| Each member has a busy lifestyle and will need to find time to coordinate requirements to the project with each members. | Team members will utilize Slack, GitHub and email to coordinate information with each other. |
|Project Member leaves or reassigned | 5 (Medium)| 10 (Severe) | 1 (Unlikely) | The loss of a team member will force other members to increase the workload to other members of the team. | Tasks will be assigned utilizing the GitHub Kanban board system. |
|Unable to learn EmberJS | 3 (Low Medium) | 6 (Moderate) | 1 (Very Unlikely) | No members of the team are able to understand or generate appropriate Ember JS code. | Ember JS has multiple resources to learn the code to be learned by members who don't know the codebase. |
|Failure to Complete Tasks in Scheduled Time | 4 (Low Medium) | 5 (Moderate)| 4 (Unlikely)| Each task has a scheduled time that it should be complete by in order to keep the project on time. | Team members assist others, if needed, with tasks that are behind schedule. Can push the timeline to complete the task if needed. |
|Design is infeasible | 5 (Medium) | 8 (Significant)| 1 (Very Unlikely)| The design of our addition to the project is overly costly or can't support the requirements | Team members will work together to be sure each feature will work with the proper design without increasing the cost immensely. |
|UI is bad quality | 5 (Low Medium) | 6 (Moderate)| 4 (Unlikely)| The UI is buggy, difficult to use, or doesn't allow tasks to be completed. | Team members will focus on testing, finding, and fixing bugs that flaw the UI. |


### Project Methodology
![Use Case "User"](/CYBR4580-8950/SupDocs/UseCase.png "Use Case User")
* Our user case model for the user remains the same. The functions will allow the user to log in, view results and take a test. The overall function will not change as previously thought. Most of the original work will remain

![Use Case "Admin"](/CYBR4580-8950/SupDocs/UseCaseadmin.png "Use Case Admin")
* The admin has been flushed out to be represented in our dashboard view. THe admin will be able to view the entire cybertrust population and recieve stats of each user and department.

![Misuser](/CYBR4580-8950/SupDocs/Misuser.png "Misuser")

## Next Milestone planning
* We will focus on providing updated visualitions from backend data, time was the enemy on milestone 2 but the informationa nd progress we gained will increase the suscess for this to be completed in the final milestone.
* Generate additional views when user clicks on a data model. For example if the admin clicks on the vitimization chart then a new display is generated without re-generating the page.
* Intergrating backend data with frontend data, both groups come together to generate one final view.

## Milestone 3

* [Project Milestone 3](/CYBR4580-8950/Project-Milestone-3.md)

# Project realization Progress Report
## Overview
The Cybertrust team has finished work on the dashboard page within the cybertrust project. The team focused more on how to display useful data to the end user and to allow the end user to be informed from both large populations as well as small populations and be able to make informed decisions.

## Outcomes
* We not only have each user ranked by victimization risk but we can view data based on this as a filer
* We are able to present data by collected demographics as well to include age, sex, education and department once those fields are populated
* We have focused on showing all members of the population ranked by the users F1 score which was more useful to the end user.
* Most information happens within the same web view with no need to push additional information
* The team successfully utilized a technique to best display data based on true positive, false positive, true negative and false negative to the end user

## Hinderances
* Ember charts was looked to be replaces and while zingcharts looked to be the solution ember charts has a more active community
* The team has moved into two teams, one visualization and the other backend data. This has improved productivity but both teams need to communicate so that the process moves faster. We are on a schedule which is being met but the complexity between the two groups makes this slow moving.

## Milestone 3 product increments

* In this milestone the team focused on presenting the data best to the end user
* The team found backend data able to be manipulated to show user victimization possibilities useful to the end user


## Final code
* Final code is within Cybertrust repo under Capstone Project 2019
