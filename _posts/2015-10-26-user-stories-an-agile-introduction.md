---
title: "User Stories: An Agile Introduction"
layout: post
date:   2015-10-26 11:15:00
categories: scrum "user stories"
tags: scrum user stories
image:
---

User stories are one of the primary development artifacts for Scrum and Extereme Programming project teams.

A **user story** is a very high-level definition of a requirement, which contains just enough information so that the developers can produce a reasonable estimate of the effort to implement it.

[Reading Material](http://www.agilemodeling.com/artifacts/userStory.htm)

A user story is a reminder to have a conversation with your customer (aka project stakeholders). Another way to put it is that is a reminder to do just-in-time analysis. They are slim, high level requirements artifacts.

User stories are small - smaller than use cases or usage scenarios:

> Students can purchase monthly parking passes online.

> Parking passes can be paid via credit cards

etc


1. **Stakeholders write user stories**: The stakeholders should write the user stories, not the developers.
2. **Use the simplest tool**: Use index cards
3. **Remember non-functional requirements**: stories can beused to describe a wide variety of requirements types. Usage requirements and technical requirements are also important.
4. **Indicate the estimated size**: Assign points to each card, relative to the other cards.
5. **Indicate the priority**: Prioritize cards, requirements, bugs, operations, etc. Project stakeholders should prioritize tasks. High/medium/low is often used.
6. **Optionally include a unique identifier**: Label cards with case numbers or some other way of maintaining traceability between the user story and other artifacts (such as acceptance tests).

Example:

> 173. Students can purchase parking passes.
>
> Priority: High
> Estimate: 4

## Formalizing the Process

> As a [role] I want [something] so that [benefit].

Mike Cohn in *User Stories Applied* suggests a fmore formal approach too writing user stories. Using the above example helps formalize the process. It helps you thinl about who a certain feature is built for and why. 

## Planning

User stories affect the following planning process on agile projects:

1. **Scheduling**: The priority assigned to each story affects when the work will be done to implement that requirement. Project Stakeholders are responsible for prioritizing requrements. **MSCW** (aka MoSCoW) - Must Should Could Won't. Stakeholders can define new requirements, but also must be responsible for making decisions and providing information in a timely manner.
2. **Estimating**: Developers are responsible for estimating the effor required to implement the things which they will work on. The size of the work items will affect when those items will be addressed. Large stories, aka **epics**, require being broken up into smaller stories in order for estimating to happen.

Working items that are high priority, and therefor at the top of the backlog should have much greater detail than those that are low priority or at the bottom of the queue.

## User Story Life Cycle

There are several distinct "phases" or **seasons** in the life cycle.

1. **Inception**: You create a stack of user stories during the requiremetns envisioning activities to identify the scope of your system.
2. **Construction**: Identify new stories, split existing stories, reprioritize existing stories, remove stories, etc. Stories evolve over time.
3. **Transition**: New stories will be identified during the transition stage (when a release is deployed). The focus of release is on hardening the system and not on new functionality.

## Detailing a User Story

User stories contain very little information. There are three common times when user stories are fleshed out:

1. **During just-in-time analysis/model storming with stakeholders**: Explore the details behind that user story. Create screen sketches with stakeholders to explore what they want. Identify acceptance criteria, or confirmations, which the stakeholders will user to validte that the user story has been implemented correctly.
2. **During iteration planning**: As part of the estimation effort, it is quite common to list programming tasks required to implement the user story.
3. **During implementation**: When you start work on implementing the user story, you may decide to create flow charts, UML activity diagrams, etc.


## Epics

Large stories are called epics, and are usually too big to implement in a single sprint. Therefore, they need to be disaggregated into smaller user stories.

Epics are usually low priority; as the epic moves up the backlog, it is fleshed out and reorganized into smaller tasks. Don't invest time on low priority epics, which may change in the future. That's the whole point of just-in-time basis.

## Themes

A theme is a cllection of related user stories. Themes are often used to organize stories into releases.
