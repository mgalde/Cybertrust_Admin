# Progress Report (28 March 2019)
## Overview
The Cybertrust team has worked on the dashboard page within the cybertrust project. The team has successfully been able to poll backend user data to publish into the frontend to show the cybertrust admin user useful data about the test subjects in a meaningful way.

## Outcomes
* We have been able to identify what individuals are ranked as low risk, moderate risk and high risk based on how the user took the test.
* We have been able to identify and represent false negative and true positive vs true negative and false positive to the user based on questions / experiments so that the end user can make useful determinations about the data.
* We have also been able to display the top 5 low performers and display their progress on the user screen so that the cybertrust administrator can take action if needed to ensure members complete the exercise.
* We have been able to generate new page views without loading a new page so that the user can review information from a single view

## Hinderances
* Ember charts utilized backend data which did not play nicely with the calculations we wished to preform. The team moved to zingcharts which added a extra step for set up. This setup caused a delay so we reverted back to the ember chart view. For visualization purposes we will likely move back to zing chart and resolve the issues.
* The team has moved into two teams, one visualization and the other backend data. This has improved productivity but both teams need to communicate so that the process moves faster. We are on a schedule which is being met but the complexity between the two groups makes this slow moving.
* Team is still trying to find best way to display False Negative and True Positive vs. True negative vs. False positive to the end user in a useful way to the end user.

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
* The admin has been flushed out to be represented in our dashboard view. The admin will be able to view the entire cybertrust population and receive stats of each user and department.

![Misuser](/CYBR4580-8950/SupDocs/Misuser.png "Misuser")

## Next Milestone planning
* We will focus on providing updated visualizations from backend data, time was the enemy on milestone 2 but the informational nd progress we gained will increase the success for this to be completed in the final milestone.
* Generate additional views when user clicks on a data model. For example if the admin clicks on the victimization chart then a new display is generated without re-generating the page.
* Intergrading backend data with frontend data, both groups come together to generate one final view.
