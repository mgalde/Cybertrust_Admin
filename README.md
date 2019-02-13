# Cybertrust

Due to the unique nature of this capstone project, the actual codebase will not be included within this repo, only the supporting documentation would be included.

* [Project Bid PDF](/ProjectBid.pdf)
* [Project Bid](/ProjectBid.md)

## Milestone 1

* [Project Milestone 1](/CYBR4580-8950/Project-Milestone-1.md)

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



### Project Methodology

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


Under your requirements section in the README.md file in your GitHub repo, clearly identify the technologies, products, and languages involved in your project. Include a table that identifies which team member will investigate each needed resource. Also include a column indicating whether or not material resources are needed from Dr. Hale.

Use the following table structure.

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
