# Progress Report (28 March 2019)
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





















# Project CyberTrust

## CYBR4580/8950 Project Milestone 2:
Non-trivial Deliverable Increment

## Overview
This project milestone tasks you with producing your first major deliverable. Since every project is different the requirements stated below are as generally applicable as possible.


- [Project realization](#project-realization) - Clearly document your efforts towards achieving the project methodology.
  - Identify tasks achieved from your backlog
  - Document the product increments (an agile term for the things you produce) generated in this milestone
  - Bind tasks, code artifacts, and documentation together
- [Process / Conceptual Model (aka diagrams)](#diagrams) - Encapsulate your efforts diagrammatically
- [Next Milestone planning](#next-milestone-plan) - Create a plan on your Kanban board for your next milestone
- [Presentation](#presentation) - Present your progress to the class



## Project realization
The bulk of the project work is centered on realizing the methodology you defined in Milestone 1. Here, you should identify the tasks you have achieved, document the product or other intellectual/applied outcomes that have resulted from your efforts, and bind your tasks to the outcomes and documentation you have produced so far.

Be productive, work towards completing your process, and document what you do.

Documentation towards project realization will come in the form an intermediate project report. Your project report should be placed on GitHub in the same repository you used for Milestone 1. Create a new markdown file that contains the following.

```markdown
# Progress Report (insert date here)
## Overview
(insert brief overview of efforts made)

## Outcomes
(brief overview of outcomes - what did you achieve?)

also list them out like this:
* outcome 1
* outcome 2

## Hinderances
(insert brief discussion of challenges encountered)

## Ongoing Risks
(address your project risks identified from Milestone 1 and update them based on your current progress, this should be a table)


```

### Submission materials
For this submission, you should submit your progress report as a `.md` file in your project GitHub repository

#### Grading Criteria
Your team will be graded as follows:

| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
| Effort and progress | It is clear that the team has made non-trivial effort and progress towards project realization.| There is some evidence of effort and progress, but more could have been done in the time. | Little effort or progress was made.|
| Documentation | Code artifacts and tasks are documented well. Documentation is clear and illustrative. | Some code is documented, but large portions are not. | Little or no documentation.|
| Demonstrable Outcomes | The outcomes are successfully demoed for Dr. Hale. The team addresses and handles questions well. | The demo partially works, but there are some significant issues. | Many significant issues with artifacts (e.g. code, documents, etc).|


**Total 120 points.**

## Diagrams
In addition to the project documentation, you should produce a set of process or conceptual diagrams suited to your project. This could be a set of activity diagrams for penetration-testing oriented projects, it could be software architecture diagrams for development-oriented projects, or it could be a process/conceptual model for other projects.

For more information about different types of diagrams, see:

Activity diagrams:
* [http://www.agilemodeling.com/artifacts/activityDiagram.htm](http://www.agilemodeling.com/artifacts/activityDiagram.htm)
* [http://www.uml-diagrams.org/activity-diagrams.html](http://www.uml-diagrams.org/activity-diagrams.html)

Process Diagrams:
* [http://asq.org/learn-about-quality/process-analysis-tools/overview/flowchart.html](http://asq.org/learn-about-quality/process-analysis-tools/overview/flowchart.html)
* [https://www.rds-london.nihr.ac.uk/RDSLondon/media/RDSContent/files/Research-process-flow-chart_A4_web.pdf](https://www.rds-london.nihr.ac.uk/RDSLondon/media/RDSContent/files/Research-process-flow-chart_A4_web.pdf)

Conceptual Model:
* [https://airbrake.io/blog/sdlc/conceptual-model](https://airbrake.io/blog/sdlc/conceptual-model)
* [http://boxesandarrows.com/conceptual-models-in-a-nutshell/](http://boxesandarrows.com/conceptual-models-in-a-nutshell/)

### Submission materials
You should create your diagrams using an architectural tool such as Lucidchart, MS Visio, or similar tools. You should include the diagram in your main project README.md file and in your Progress report in your GitHub repo, as an image and/or link to Lucidchart.

### Grading Criteria
You should have produce **at least three diagrams** relevant to your project, each will be graded as follows:

| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
| Relevant | The diagram is useful for conveying project details. | There are some issues that prevent the diagram from contributing to understanding | The diagram is tangential or not present. |
| Descriptive | The diagram clarifies the interoperation or operation of a feature of interest. It provides descriptive clarity. | The diagram provides limited descriptive clarity. | The diagram doesn't help the viewer understand the process/model/architecture. |

**Total 60 points.**


## Next Milestone planning
Plan the next milestone. In the next (and final milestone) - you will 1) continue to work towards realizing your methodology, 2) polish your product/outcomes and prepare them for release, and 3) aggregate your results into a single final report for release to vendors or other relevant entities.

### Submission materials
This part of the milestone is strictly captured by your Kanban board. In your Kanban board, create a board following the structure used in Milestone 1. Use this structure to identify the tasks that you will tackle in your next sprint. Put those tasks in the **Sprint To-do** category.

### Grading Criteria
**Total 30 points.**

## Presentation
You will be expected to present your Milestone 2 achievements to the class following the deadline. It is important that you use this time to both inform your classmates of your activities and to practice for your final presentation. Things to be considered are 1) conveying a sense of interest and excitement about your project 2) cool product demos, and 3) interesting findings of conducting your projects.

### Submission Materials
Submit your slides to Dr. Hale by the presentation days (TBA on slack). Submit them by posting and pinning them in your team slack channel.

### Grading Criteria
You will be graded by a presentation rubric TBA.

**Total 60 points.**



- [Executive Project Summary](#executive-project-summary) - @jarob00
  - Goals and Objectives
  - Merit of the Project
- [Proposed project timeline](#proposed-project-timeline) - @mgalde
  - Define the tasks and expected time to completion
  - Create and submit a gantt chart
- [Project-oriented risk list](#risk-list) - @mgalde / @AustinNielsen
- [Project Methodology](#project-methodology) - @swrp / @mgalde / @jarob00 / @AustinNielsen
- [Resources/Technology needed](#resources-needed) - What do you need to be successful? - @fkangaye
- [First Sprint Plan](#first-sprint-plan) - @swrp
- [Note about Teamwork and Group projects](#teamwork)
