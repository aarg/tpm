+++
title = "Bug Tracking"
description = "How to design bug tracking process"
tags = [ "TPM", "Jira", "Bug tracking", "Reporting" ]
weight = 2
+++


<div class="align-left py-4">
  <img src="/bugs_tracking.png" class="img-fluid " alt="Roles">
</div>

## Bugs (defects or features) Tracking

In most organizations, Software Engineering teams are organized into logical groups e.g. backend infrastructure, feature backend, frontend infra, UIs, feature teams, etc. Whereas most of the projects would require work across many Engineering teams. As a TPM, your role is to create a structure and organize the work across teams to hit project milestones as per timelines defined by you. Apart from your Project trackers (Spreadsheets, MS Project, Asana, etc.), a bug tracking tool is an essential element of project tracking. Bug tracking is the closest source of truth for visible progress. Typically, Engineers assign the bugs to the appropriate person, and the progress is captured on the bug. They attach code changes to the bug or define blockers/dependencies within the tool. Progress reporting is generally built on top of such bug tracking tools.

I will stay away from tool usage itself. Jira, Bugzilla, Tracs etc., are just means to track progress. As a TPM, you still need to define and design the use of these tools. There are two essential things to keep in mind as you create the workflow for a bug tracking tool:
* People and interactions
* Progress tracking and reporting

### People and interactions

Stakeholders use bug tracking tools in different ways. Engineering managers are interested in things like Next priorities, their team’s current workload, the team’s velocity, and what needs to get done by when. PMs are interested in knowing what remains to complete the feature, when it will get done, and if anything is blocked. Release managers want to know what all is checked-into the binary, is the binary ready to be released.

It may take several layers of triage in a complex organization before a bug gets to the right Engineer. It’s essential to have a defined consistent process for how the bug flow through various triage and eng teams levels. Optimize for speed and accuracy - getting these things wrong has an associate cost. Sometimes, it’s best to create a clear runway for high priority/production bugs, whereas it might be ok for normal priority bugs to follow a regular workflow.

As Engineers start working on bugs, they often need to assign them to a different team. As a TPM, ensure that people have clarity on engagement rules for such re-assignments e.g. priority definitions and Need by dates are mentioned in the tools. You will need separate mechanisms to align on deliverables, priorities, and timelines.

### Progress tracking and reporting

As you design the workflow, think about things essential for you to know and report. Few key reports to keep in mind:

* Progress towards the next milestone: Create a chase list of what’s remaining, when is it expected to get done, and who’s working on it?
* What are the open items for any project at a given point?
* What’s being actively worked upon, and what’s the backlog
* Workload per eng team
* The velocity of each eng team