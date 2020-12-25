+++
title = "Project scoping"
description = "How to define scope for software projects"
tags = [ "Project Scoping" ]
weight = 6
+++

The project scoping is helpful to estimate the timeline and resources required
to get the project done. To start this exercise, we need a basic set of project
requirements and a core team to help scope the project. It will help answer the
following questions:
* what are the big blocks of work?
* complexity of the work involved
* project dependencies
* critical path to project milestones
* time estimate to get the work done

In this article, we will take an example of building a Weather App and walk
through a complete scoping exercise. 

Make a
[copy](https://docs.google.com/spreadsheets/d/10boe95t51bsFUF2K53IBXGxHsquJzdUvoJuEymURCV0/copy)
of the below spreadsheet to follow along. 

1. Based on the Product Requirements Doc (PRD), make a list of all the big-block
   tasks for the project. Don’t worry about the accuracy of this list at this
   stage, try to get a ball-bark distribution of tasks amongst different teams.
   Leads in various teams can help. This list is represented in the `Weather
   App` tab of the spreadsheet. 

2. **Definitions**
   1. **Milestones:** In this context, there are two important milestones 1.
      Prototype to determine the feasibility of project 2. Min Viable Product or
      the set of deliverables required for shipping the product. In addition, we
      can add more post-launch milestones. For this exercise, I skipped the
      Prototype milestone and used **M1** to designate MVP. <br>
      <div class="text-center">
        <img src="/project_scoping_milestones.png" class="img-fluid " alt="Milestones" width="300" height="300">
      </div>
   2. **Priorities:** To keep it simple, all P0 tasks are absolutely needed for
       the milestone. P1s are important and P2s are nice to have. <br>
       <div class="text-center">
         <img src="/project_scoping_priority.png" class="img-fluid " alt="Priority" width="300" height="300">
       </div>
   3. **Sizing:** Using the t-shirt sizing approach to get a ball-park number
       for the amount of work to be done. Don’t worry about the accuracy of the
       scope at this stage. Try to break down the tasks so that they are smaller
       than XL; this will result in better scoping accuracy. This is per person
       effort, if the task can be done faster by more people in parallel then we
       will reflect that during the scoping exercise. <br>
       <div class="text-center">
         <img src="/project_scoping_sizing.png" class="img-fluid " alt="Sizing" width="300" height="300">
       </div>
3. **Weather App scoping:** Now we have the list of the tasks that each team needs
   to work on to deliver the product. Next steps:
   1. Define the milestone, priority, and size guesstimate for each task. 
   2. Guesstimate the number of people required to work on the task. Ideally,
      each task would be done by 1-3 people. You will get better results if the
      number of people required is small. Put the names of potential people who
      will be working on the task.
   3. Create a flat list of tasks as done in the ‘timeline’ tab of the
      spreadsheet. This helps with sorting and mapping dependencies.
   4. Stack rank the tasks in the order they need to be executed, note down the
      dependencies in col J. If the task is not dependent on anything else then
      that can be started in parallel to other tasks or as soon as people are
      available to work on it.  If you know that few tasks can be done in
      parallel e.g once the basic technical design is complete, the server and
      client team can work independently. For such, parallel tasks, give them
      the same stack rank numbers.
   5. Depending on the order of operations, fill out the estimated start date in
      col H.
4. **Learnings from scoping exercise:** <br>
   <div class="text-center">
       <img src="/project_scoping_learnings.png" class="img-fluid " alt="Learnings" width="300" height="300">
   </div>

   1. Assuming the team starts on 4-Jan, Weather App is expected to be code complete by 7-Jun. 
   2. Assuming the team needs another 2+ weeks of final QA and launch preparation, expect to set the launch date to 10-May. 
   3. As seen in the ‘Weather App’ tab, the Eng team will have to compensate for few resource gaps, for this exercise we incorporated those gaps into the timeline tab as sequential work. In other words, there are opportunities to expedite the work if we had more people.
5. **Further enhancements:** The scoping exercise did not accommodate for buffer
   and vacation time. Typically, I’d add another 25-50% of buffer time for
   unknowns and risks. Practically, the M1 launch date might be **end of May**. 

## Project Scoping spreadsheet

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTHWluzRzh5-gDzf66T3bO7IDck-J82_RS0Cwqx3r7-FVdVq3PptKgOnQS5J6b316KDAW0ag2J_6_Om/pubhtml?widget=true&amp;headers=false" width="800" height="800"></iframe>

