+++
title = "PM, PgM, TPM vs TL"
description = "Compare PM, PgM, TPM and other related roles"
tags = [ "TPM", "PM", "PgM", "TL", "TPM" ]
weight = 4
+++


From Michael Lopp's randsinrepose.com [blog](https://randsinrepose.com/archives/entropy-crushers/):

{{< panel style="primary" >}}
*A program manager is an uber-mutated combination of both that usually shows up to handle multiple interrelated projects like, say, an operating system. Different companies use the names differently, but for this article, project = ship the product, product = ship the right product, and program = ship many interrelated products, usually at the same time* {{< /panel >}}

<div class="text-center">
  <img src="/roles.png" class="img-fluid " alt="Roles">
</div>

## PM: Product Manager

The Product Manager is responsible for defining what needs to happen and why. For any Software development project, a PM would work with the team to figure out the right product to develop. PM considers various factors to get to the definition of the product:

* **Customer value:** Does the product add value to its users? What's the change
    this product brings in customer's usage of the product? Does it make the user's
    life easier / better / delightful?   
* **Marketing fit:** Is there a real need for such a product?
* **Time to market:** Are there any external factors controlling the launch
    timeline? Any competing products, do we want to gain a first-to-market
    advantage?
* **Time to develop:** How long does it take to develop the product?
* **MVP:** What's the minimum viable product that can be shipped and serves
    its purpose?
* **Defining success:** What's the purpose of the product? What metrics would
    we measure the success against? Define success based on the product maturity
    e.g customer segment and market penetration for new products or revenue for
    matured products.
* **Product features:** Break down the product into a well-defined set of
    features. Describe the product usage workflow from the user's perspective.

Product definition is generally written in the form of a 'Product Requirements
Doc' (PRD). This definition is expected to evolve during the product development
lifecycle as new information comes in.

A PM works with a lot of different cross-functional groups:

* A PM would work very closely with the Program Manager during the project’s execution phases to align priorities.
* A PM would work very closely with Tech Lead to ensure Engineering builds
  the product as the PM defined.
* A PM would work very closely with UX to get the right designs.
* A PM would work very closely with marketing to align on all external factors
  influencing product design and launch.
* A PM would also work closely with other cross-functional groups such as
  Legal, Privacy, and Security to ensure the product is doing the right thing.

## PgM and TPM

**PgM: Program Manager**
**TPM: Technical Program Manager**

For the most part of this site, I have used PgM and TPM interchangeably.
The primary responsibilities for both of these roles are still the same. However,
TPMs are more involved in the technical aspects of their projects. In this
context, technical implies software development. Apart from core Program
Management, here are few examples of what a TPM on  a project could be doing:

* Based on the PRD, a TPM could write the technical specifications for a project.
  Such a document would help Engineers understand the technical aspects of the
  requirements.
* A TPM generally understands the software architecture and influences technical
  choices. This influence typically comes from past experiences or the ability to understand various technical paths.
* A TPM is expected to demonstrate technical judgment during various phases of
  the project e.g help with code path optimizations, user latency optimizations
  etc.
* A TPM could also contribute to software development/code. Generally, this
  might not be a good idea as it takes time away from core job responsibilities.
  And, it is unlikely that a person is good at coding and managing the project
  simultaneously.
* Few more specific activities that a TPM could be doing as a technical
  contribution to the projects:
  * QA/ Test automation + API validation
  * Release management
  * Platform / Infra management e.g managing AWS/Cloud resources. Managing App
    store releases via App Developer Console.

## TL: Tech Lead

The Tech lead's primary responsibility is to drive all technical aspects of the
project. This is usually seen in the form of architecture or design docs,
figuring out an optimal path to deliver code, including technical dependencies,
unblocking Software Engineers on technical decisions etc.

## TLM: Tech Lead Manager

TLM usually has few Software Engineers reporting to them and has the
authority to allocate people to projects. They are responsible for the career growth
and productivity of individuals reporting to them. They have a good sense of mapping people to project.


## TPM Relationships

Most of the successful projects I have been on have a strong trio
relationship: PM, TPM and TL. All three roles work very closely with each other.
Although they have very distinct roles, they can often represent each other in various meetings.  This kind of strong bonding and trust
relationship takes time and requires deliberate, conscious effort to develop.
As a TPM, nurturing such a relationship with your PM and TL is part of the job.
