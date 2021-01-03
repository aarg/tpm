---
title: "TPM Role"
weight: 3
---

<div class="text-center">
  <img src="/TPM_role.png" class="img-fluid" " alt="TPM Role">
</div>


## What does a TPM do?

The role of TPMs can be quite diverse, depending on the organization, and the
stage of the project. This gives TPMs a great deal of freedom to do their work,
but it also makes it harder to define success. Navigating the ambiguity of the
role may sometimes prove difficult. In this section, we will discuss some
examples of things and activities that a TPM does in their day-to-day
activities. This is not an exhaustive list, and TPMs do not do everything that
is indicated here. We will explain later what is needed to be [successful](/how)
in the role.

This section is divided into two parts:  [**TPM Role -
Basics**](#tpm-role-basics) covers the core set of responsibilities a TPM might
assume on any project. [**TPM Role - Specialized**](#tpm-role-specialized)
covers more specific topics related to org, project phase, or specialized skill
set.

### TPM Role - Basics{#tpm-role-basics}

Generally, the PM defines what needs to happen and TPM is responsible for
getting it done. PM vs TPM role details [here](/what/roles). TPMs are
responsible for the execution of the projects and are expected to work through
various aspects of product delivery. Some of the things a TPM does are the
following:

* **Get the right team in place:** During the initial phases of a project a TPM
  works with PM to figure out who all are needed to successfully execute the
  project. For any typical software project this team structure would consist
  of: Software Engineers (Backend and Frontend), Infrastucture Eng, QA,
  UI/UX designers, Privacy, Security, Legal and Marketing folks. Obviously,
  each project is different and may require few other roles. At the beginning
  of the project, a TPM (or PM) would reach out to all contributors or
  stakeholder to setup the right team structure of the project.

* **Project Scoping:** Irrespective of the Project tracking tools a team uses, the TPM must spend some time at the beginning of the project to scope out the work. This is not an exercise to determine the launch date, but rather to figure out things like:
    * what are the big blocks of work
    * what's the complexity of the work involved
    * what are the dependencies
    * what's the critical path to finish timeline
    * what's the time estimate to get the work done

  <br> This exercise will help the team to figure out what areas of the project to spend more time on and also to assess the magnitude of the project. It gives an initial estimate on the feasibility of delivering the project by a certain time-frame.

* **Setup Project structure:** Sometimes also referred to as Governance or Execution structure, as a TPM you need to establish a standard set of practices to run the project. List of artifacts that help setting up such a structure:
    * Project workstreams
    * Project and workstream leads
    * Trackers:
      * Milestones
      * Timelines
      * Tasks
      * Features implementation progress
      * Bugs
    * Central Project site or wiki for one place to link all project related
      information
    * Setup distribution list (or email groups)
      * leads group (few people)
      * working group (all people working on the project)
      * stakeholders group (all people interested in receiving project related
          communication)
    * Communication format
        * Periodic newsletters
        * Meeting notes
        * Exec presentations
    * Testing results progress and analysis
    * Gathering user feedback

    <br>You can find more details about execution structure [here](/how/how_governance).

* **Drive the project:** The project structure helps you drive the project forward. Program Managers need to be disciplined enough to run the processes that have been established and agreed upon with the team. The team depends on program managers to bring clarity on the status of the project and highlight if things are going sideways. Driving a project means doing activities like: tracking the tasks, milestones and timelines, managing dependencies, unblocking if things are not moving forward, communicating the status, setting the required meetings and reviews.

* **Manage testing and beta usage:** As features get coded, help the team get them tested via manual QA or automated test infrastructure.
Many organizations use the concept of beta testing the product with a small group of real users. Beta testing helps uncover real-life scenarios that might have been missed during product development. Program Managers may help the team run this process by: 1. Figure out the cohort of such users. 2. Share the product with them - this may mean to run a specialized release process for these limited set of users 3.Help users discover product features and usage 4. Collect feedback 4. Analyse feedback - qualitative (e.g CSAT scores, generic feedback on what worked and not) or quantitative (bugs discovered during product usage) 5. Follow-up on feedback/bugs with Product and Eng teams.  

* **Manage releases and launch:** Setup the process for getting code to production. TPMs are closely involved and sometimes even drive the entire process of periodic binary releases. Product launch is a lot more involved process: teams start preparing for this activity quite early in the product development life cycle. <WIP>

* **Conclude the projects with postmortems:** It’s always a good practice to end the project with a postmortem or a retrospective. Define a common template that each sub-team can use to fill up the details, this would typically be divided into 2 primary categories: What went well? And, What can be improved? You might also want to get feedback on any new specific things you introduced related to the program or processes.

### TPM Role - Specialized{#tpm-role-specialized}

As the programs grow bigger, TPMs can be hired for specialized roles. If the organization has resources, a good way to scale is to build expertise for various functions. This also helps with the establishment and improvement of standard processes. TPMs in these roles are not only responsible for launch of specific programs, but their success is dependent on how well the process is run in support of the program, their core responsibility is to establish a process and constantly work on improving it. Here are a few examples of specialized roles and a brief description of each of them.

* **Release management:** Binary release is an important function for any software organization. It is essential that every release maintains (or improves) the quality of shipping software. At a very high level, a TPM would perform the following activities as part of the Release management process:
  * Create a release schedule, publish a release calendar.
  * Publish a step-by-step release process
  * Host release planning meetings
  * Define mitigation strategies when things are not on-track e.g blocking bugs, non-deterministic feature quality,  rel-eng issues etc…
  * QA qualification of binary
  * Push the binary through various internal stages before hitting prod
  * Monitor prod metrics after pushing the binary to prod

Depending on the product and binary hosting environment, many of the above steps are automated and might not even require a TPM involvement. This is more common for teams that ship server binaries very frequently (~daily)  to production.

* **QA management:** The job of Quality Assurance is to test and ensure good quality of the shipping software. A TPM in this function manages the QA lifecycle for qualifying the binary or feature before shipping to production. This would require a good understanding of automated vs manual test cases, prioritizing the test cases and ensuring teams have the right setup for testing. Once testing is complete, a TPM would analyze the results and assess the severity of the issues found.

* **Beta usage management:**  Many organizations use the concept of beta testing the product with a small group of real users. Beta testing helps uncover real-life scenarios that might have been missed during product development or structured testing. A TPM in this function helps the team run the beta usage process by: 1. Figure out the cohort of such users. 2. Share the product with them - this may mean to run a specialized release process for these limited set of users 3.Help users discover product features and usage 4. Collect feedback 4. Analyse feedback - qualitative (e.g CSAT scores, generic feedback on what worked and not) or quantitative (bugs discovered during product usage) 5. Follow-up on feedback/bugs with Product and Eng teams.  

* **Launch TPM:** For large programs, many organizations designate a formal launch TPM role with the objective of having a person coordinating all the things required to launch the product. This person would work closely with many groups including Engineering, Product, QA, SRE, Core Infrastructure, Privacy, Security, Marketing etc… A launch TPM would coordinate the readiness of launching the product across various functions in the organization.  

* **Feature TPM:** A feature TPM gains subject matter expertise on specific features and coordinates the work required to ship them to production. Although it’s not a common practice to hire feature specific TPM, there are two scenarios where this is helpful: 1. When the feature is complex and requires coordinating a lot of dependencies across various teams 2. This is a good way for junior TPMs to learn the skills, having a smaller scope of work helps with the learning process.

* **Infrastructure TPM** partners with Engineering teams to coordinate the work related to compute platforms and services. In most of the modern organizations, this role is responsible for things like: managing cloud infrastructure, networking  or developing backend infrastructure and tools that the rest of the Engineering organization depends on.

* **Cloud Capacity management TPM** role is closely related to Infra TPM, an even more specialized role to manage cloud infrastructure capacity.  It involves working with Engineering teams and figuring out the compute, networking and data storage requirements for various features
