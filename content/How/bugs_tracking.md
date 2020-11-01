---
title: "Bug Tracking"
date: 2020-08-23T12:08:02-07:00
---

<div class="align-left py-4">
  <img src="/bugs_tracking.png" class="img-fluid " alt="Roles">
</div>

## Bugs (defects or features) Tracking

In most of the organization, Software Engineering teams are organized into logical groups e.g backend infrastructure, feature backend, frontend infra and UIs, feature teams, etc…Whereas, most of the projects would require work across many Engineering teams. As a TPM, your role is to create a structure and organize the work across teams to hit project milestones as per timelines defined by you. Apart from your Project trackers (Spreadsheets, MS Project, Asana, etc…), a bug tracking tool is an essential element of project tracking. The thing I like most about the bug tracking tool is it is by far the closest source of truth for visible progress. Typically, bugs are assigned to Engineers and they are expected to update the progress, attach Code changes, or define blockers/dependencies within the tool. Progress reporting is generally built on top of such bug tracking tools.


I will stay away from tools usage itself. Jira, bugzilla, Tracs etc...are just
means to track progress. As a TPM, you still need to define and design the
usage of these tools. There are two important things to keep in mind as you
design the workflow for a bug tracking tool:
* People and interactions
* Progress tracking and reporting

### People and interactions

Stakeholders use bug tracking tools in different ways. Engineering managers are interested in things like Next priorities, their team’s current workload, the velocity of the team, what needs to get done by when. PMs are interested in knowing what all is remaining to complete the feature, when will it get done, and if anything is blocked. Release managers want to know what all is checked-into the binary, is the binary ready to be released.

In a complex organization, it may take several layers of triage before a bug gets to the right Engineer. It’s important to have a defined consistent process for how does the bug flow through various levels of triage and eng teams. Optimize of speed and accuracy - getting these things wrong has an associate cost. Sometimes, it’s best to create a clear runway for high priority/production bugs, whereas it might be ok for normal priority bugs to follow a regular workflow.

As Engineers start working on bugs, many times they need to assign it to a different team. As a TPM, ensure that people have clarity on rules of engagement for such re-assignments e.g priority definitions and Need by dates are mentioned in the tools. You will need separate mechanisms to align on deliverables, priorities, and timelines.

### Progress tracking and reporting

As you design the workflow, think about things important for you to know and
report on. Few key reports to keep in mind:
* Progress towards next milestone: A chaselist of what's remaining, when is
it expected to get done and who's working on it.
* Progress towards next milestone: A chase list of what’s remaining, when is it expected to get done, and who’s working on it.
* What are the open items for any project at a given point
* What’s being actively worked upon and what’s the backlog
* Workload per eng team
* Velocity of each eng team
