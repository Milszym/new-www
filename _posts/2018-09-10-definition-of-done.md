---
layout: post
title: Definition of Done
author: mateusz
tags: ['programming practices', 'project management']
comments: true
hidden: true
image: /images/definition-of-done/dictionary.jpg
---

I have often heard that something is "almost ready". This term is vague and brings more confusion than information. According to the [Ninety-Ninety rule](https://brightinventions.pl/blog/dont-be-mockup-developer/#ninety-ninety-rule), 90% of the code is implemented during 90% of the project time and the remaining 10% of the code ("almost ready features") can take even the same amount of time which would lead to massive project delays.

For this reason, I find determining the Definition of Done and sticking to this crucial for every project. Otherwise, you can only hum the Sad Project Manager song:
>What is done?
>
>Devs don't hurt me
>
>Don't hurt me
>
>No more

## There is no single definition

Definition of Done should be determined at the beginning of each project.

![Dictionary image](/images/definition-of-done/dictionary.jpg)

## Task stages

In the projects I run, I not only establish the Definition of Done but I also describe the task stages. To satisfy the Definition of Done all stages has to be completed. It reduces the risk of misunderstanding the workflow and allows me to verify at what stage the task is. Additionally, if the task stays for too long at some phase, it is a signal that something might be wrong.

Example task stages I use:
- Open
  - Waiting for assignment
- In progress
  - Assigned, work in progress (WIP)
- On hold*
  - Optional, in case the work cannot be continued
  - Action required (AR)
- Implemented/Ready for review
  - Code with unit tests has been committed to the repository
  - Waiting for peer review (feature testing + code review)
- Deployed/Ready for QA
  - Passed peer review
  - Deployed to staging environment
  - Client can test the feature
- **Done**
  - Passed acceptance tests
  - Changes are ready to be deployed to production environment

Bear in mind that stages depend on many factors like the peer review process, testing environments and the deployment process, acceptance testing and the way we cooperate with the client. Like the Definition of Done, these are never fixed and should be determined for each project individually.

## Win-Win

![Happy image](/images/definition-of-done/happy.jpg)

Clear workflow and unequivocal Definition of Done are necessary for the smooth work of the team. When the project manager is well informed about the progress and possible delays he can communicate it well to stakeholders. In case of any obstacles, the project manager can respond quickly and facilitate the development process. On the other hand, developers do not have the stressful feeling of prolonged work over the feature because it is divided into clear phases. No more "almost ready features" is beneficial to the whole team as it reduces misunderstandings and allows you to notice the problems that occur much earlier.