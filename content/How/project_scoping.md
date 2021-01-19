+++
title = "Project scoping"
description = "How to define scope for software projects"
tags = [ "Project Scoping" ]
weight = 6
+++

The project scoping is helpful to estimate the timeline and resources required to get the project done. To start this exercise, we need a basic set of requirements and a core team to help scope the project. It will help answer the following questions: 

* What are the big blocks of work?
* The complexity of the work involved
* Project dependencies
* The critical path to project milestones
* Time estimate to get the work done

We will take an example of building a Weather App and walk through a complete scoping exercise. 

Make a
[copy](https://docs.google.com/spreadsheets/d/10boe95t51bsFUF2K53IBXGxHsquJzdUvoJuEymURCV0/copy)
of the below spreadsheet to follow along. 

1. Based on the Product Requirements Doc (PRD), make a list of all the project’s
   big-block tasks. Don’t worry about this list’s accuracy at this stage; try to
   get a ball-bark distribution of tasks amongst different teams. Leads in
   various groups can help. This list is represented in the `Weather App` tab of
   the spreadsheet. 

2. **Definitions**
   1. **Milestones:** For project scoping, there are two critical milestones 1. Prototype to determine the feasibility of project 2. Min Viable Product or the set of deliverables to do before shipping the product. Also, we can add more post-launch milestones. For this exercise, I skipped the Prototype milestone and used **M1** to designate MVP.
   <br>
      <div class="text-center">
        <img src="/project_scoping_milestones.png" class="img-fluid " alt="Milestones" width="300" height="300">
      </div>
   2. **Priorities:** To keep it simple, all P0 tasks are absolutely needed for
       the milestone. P1s are important and P2s are nice to have. <br>
       <div class="text-center">
         <img src="/project_scoping_priority.png" class="img-fluid " alt="Priority" width="300" height="300">
       </div>
   3. **Sizing:** Using the t-shirt sizing approach to get a ball-park number
      for the amount of work to be done. Don’t worry about the    accuracy of
      the scope at this stage. Try to break down the tasks so that they are
      smaller than XL, resulting in better scoping accuracy. TThis is per person effort; if the task can be done faster by more people in parallel, we will reflect later during the scoping exercise. 
      <br>
       <div class="text-center">
         <img src="/project_scoping_sizing.png" class="img-fluid " alt="Sizing" width="300" height="300">
       </div>
3. **`Weather App` scoping:** Now, we have the list of the tasks that each team needs to work on to deliver the product. Next steps:
   1. Define the milestone, priority, and size guesstimate for each task. 
   2. Guesstimate the number of people required to work on the task. Ideally, each task   would be done by 1-3 people. You will get better results if the number of people required is small. Put the names of potential people who will be working on the task.
   3. Create a flat list of tasks as done in the ‘timeline’ tab of the spreadsheet. This helps with sorting and mapping dependencies. 
   4. Stack rank the tasks in the order they need to be executed. Note down the dependencies in col J. Note that you can assign the same stack rank if the tasks can be done in parallel. e.g., once the necessary technical design is complete, the server and client team can work independently.
   5. Depending on the order of operations, fill out the estimated start date in
      col H.
4. **Learnings from scoping exercise:** <br>
   <div class="text-center">
       <img src="/project_scoping_learnings.png" class="img-fluid " alt="Learnings" width="300" height="300">
   </div>

   1. Assuming the team starts on 4-Jan, Weather App is expected to be code complete by 26-Apr.  
   2. Assuming the team needs another 2+ weeks of final QA and launch preparation, expect to set the launch date to 10-May. 
   3. As seen in the ‘Weather App’ tab, the Eng team will have to compensate for a few resource gaps. For this exercise, we incorporated those gaps into the timeline tab as sequential work. In other words, there are opportunities to expedite the work if we had more people.
5. **Further enhancements:** The scoping exercise did not accommodate for buffer
   and vacation time. Typically, I’d add another 25-50% of buffer time for
   unknowns and risks. Practically, the M1 launch date might be **the end of May**. 

## Project Scoping spreadsheet

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTHWluzRzh5-gDzf66T3bO7IDck-J82_RS0Cwqx3r7-FVdVq3PptKgOnQS5J6b316KDAW0ag2J_6_Om/pubhtml?widget=true&amp;headers=false" width="800" height="800"></iframe>

