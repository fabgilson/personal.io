+++
author = "Fabian Gilson"
title = "Teaching about Scrum with paper"
date = "2021-09-24"
description = "How we teach about Scrum events and principles by building cities"
tags = [
    "teaching",
    "active-learning",
    "scrum"
]
+++

I'll talk about how we teach about Scrum events and principles in a gamified context. First of all, the whole credit goes to [Sonja Hof et al.](http://dx.doi.org/10.1145/3059009.3059043). You may check their paper (just click on Sonja's name, it's a hyperref) that we modified a little and tried to adapt to fix the issues they witnessed in their experiment. One day, I actually should try to contact that team to see if they still do this tutorial and if they changed anything.

## Scrum? Please don't teach that c\*\*p

I know, but please, let's try to consider Scrum in its broader (lighter? less dogmatic?) sense. Just forget about the fact that nobody can effectively continuously sprint without delivering poorly designed stuff. But let us consider the following good aspects of Scrum:

- as proposed in the [agile manifesto](http://agilemanifesto.org/principles.html), a team reflects on their process, performance and behaviour;
- also as proposed by the manifesto, a team ships often;
- Scrum asks for cross-functional knowledge and team empowerment, also agile manifesto principles;
- because it is rather structured, it fits well in an academic context.

I actually praise myself not to completely follow **the** Scrum guide when teaching about it (a regular subject of arguments and disagreement with some colleagues, actually) and I engage students in a deeper reflection about Scrum (e.g., problem about long sprint commitments, continuously deliver more, sprints after sprints with no cooldown).

## Convinced? Let's move on to the nice part

To teach about the Scrum principles (well, actually, these are more about _"behave in a team, do the job you promised, help and respect each other"_, something that is also the case in real life) and events (again, almost everything comes from other places e.g., user stories, vertical slices of the cake for tasks, sit back and think), we organise two tutorials:

- one simplified version of two sprints where we prepare a detailed plan with stories being tasked and ordered for students;
- the second tutorial adds the planning phase, students need to write the tasks and we assess their behaviour (based on [Scrum's five values](https://www.scrum.org/resources/scrum-values-poster)).

During both tutorials, students develop a city out of paper (basically).

### So they do not develop?

Students don't develop in this tutorial because the focus is not programming, but understanding the value of iterative development including negotiating with the client, tasking the work to do and reflecting on the team's performance and behaviour.

Students do have the opportunity to practise in a year long project course about the real stuff, but the goal of this tutorial is to give a first taste for students that wouldn't take the project aside this course. It's also a good introduction for the ones enrolled in the sister project course, i.e. to learn about the basics in a practical way and relatively fast.

### Preparation and admin stuff

Students are put in teams (the same over the two tutorials) and receive the explanation of the tutorial and backlog in advance. They are asked to be prepared before coming to the tutorial and, if need be, to write down some questions they'll be able to ask at the beginning of the session.

All students are considered _developers_ and we have tutors (or myself) looking after one team and acting as Scrum master and product owner (I know these two are supposed to be different, but we're short on staff).

All teams have their own space to work and display their board. We also print the backlog with all stories and tasks (for the first tutorial only) for them. The whole idea is to build a model city for a game and each team can select their theme (e.g., medieval or post-apocalyptic like Mad Max).

### What's the backlog composed of?

As an example, here's a story with its tasks (first tutorial, the stories for the second tutorial have no tasks predefined):

```
Title: Bridge
Points: 3
Sprint: 2
Sequence: 1
Description: As Reiko Rash, I want there to be a bridge so that players will be able to cross the river.
Acceptance criteria:
  - A model bridge has been added to the base board.
  - The bridge is positioned as per the street plan.
  - The bridge spans the river.
  - The bridge does not impede the flow of water or river traffic, i.e. a boat may still pass under.
Tasks:
  - Choose a spot for the bridge where a street pass nearby.
  - Define a strategy for the structure of the bridge.
  - Build the bridge according to selected strategy.
  - Stick the bridge to the base board.
```

The `points` are estimates of the complexity and the `sequence` requires students to implement this story as the first one of their second `sprint`.

### Coloured paper, scissors & glue

Each team receives a box of material to build their city including a wide base board, sheets of coloured paper, scissors and glue. They have a limited number of these to learn a little bit about how to organise shared resources between them and ensure they have good work habits where they avoid creating a such a mess that they can't find anything anymore.

Each event in the sprint is timed-box (which may sometimes make it feel like _"chaos"_) and each sprint is reviewed by the teaching staff member acting as the product owner. Teaching staff (acting as scrum masters too) also poke students during the sprint work to put them on track if they observe random things happening, but they do not lead or guide actively the sprint work.

### Two sprints + two sprints

As I said earlier, the first tutorial encompasses two simplified sprints, including a time to reflect after each sprint. Students also need to take pictures as they progress to document their work and how their city grows. We usually do not let teams carry stories over a second sprint even if it does not pass (students learn the hard way what AC means) because we want to concentrate on their ability to organise the work, not so much on the delivered product (yet).

For the second instance, teams need to plan each sprint and prepare a commitment with the product owner. **At first, most teams completely ignore the PO** when doing their planning and some even decide which stories to deliver without involving the PO. This is exactly where we want them to fail (at least one of the many pitfall we somewhat expect), because they will probably remember to never again ignore the client (hopefully).

## What do we learn from this as educators

There is a whole lot of things the students learn after going through this tutorial (e.g., some jargon, some experience with tasking, what is an actual _action item_ and why we insist so much on SMART tasking). But I don't want to go too deeply here (just flick me an email or contact me with any of the ways visible on the left).

There are many takeaways I learned as an educator that, since, have influenced how I teach some aspects of software engineering.

### Tasking is hard

The biggest issue students face is their ability to create meaningful tasks from stories. We do talk about this in lectures with some exercises (or _Kahoot!_), but when they have to do it by themselves, they learn the hard way that _the devil is in the details_.

Teams usually struggle to get their tasking right for many reasons:

- tasks are written in a rush as they talk during planning (aka planning 2 in Scrum) and they believe anyone will be able to remember what it means when it's picked up;
- acceptance criteria are often forgotten when tasking, where students concentrate on the story and their own perception (remember when I said the PO is there to make up the numbers?);
- they sometimes come with macro-tasks taking ages, hence blocking other tasks to be achieved (so they finally don't deliver much because of people stuck in deadlocks);

Linked to the problem of tasking, they forget to keep the team updated (through their board) and it happens that tasks are done twice, creating some frustration.

So, from this, I learned that tasking is hard (I know, looks like obvious), but just try to ask google and you'll see that there is no real answer to how to do this right except by referring to general guidelines. I mean that it requires experience (students sometimes believe they have) and it takes patience to help them becoming more confident, in the right way, including their ability to know the boundaries of their knowledge. And this leads to my next point, teaching about _reviews_ is hard too.

### Even if students carry some sort of review, they miss quite a few things

First things first, students (at least ours) usually are kind with each other, even when reviewing the outcome of each other tasks. They learn that some sort of peer review before marking a task done increase their performance during the first tutorial, especially after failling the first or even second sprint quite badly.

However, what only the best ones see as improvements is to review their tasking while doing the planning, especially the time estimates. Because of the time pressure, they usually split the stories and write the tasks in smaller groups (something most teams implement during the first sprint on tutorial 2, so the very first time they need to write the tasks). But very few foresee the importance of reviewing the tasks to make sure they are SMART (and readable).

This leads me to increase the amount of material and number of exercises or activities I do around peer review (i.e. tasks **and** code). There is a big bunch on things about that on the internet, especially the work of [Michaela Greiler](https://www.michaelagreiler.com/).

### Assessing the team behaviour over a 2 hour session is mostly pointless

Something I wasn't expecting so much is that, as one of the tutors working with me this year told me, _"Students can behave properly for two hours"_ (almost _sic_). Even with a lot of time pressure, the two hour tutorial (only the second instance is assessed) is not long enough for students to start getting into arguments. Not that we want fights to happen, but we know it happens from experience in the sister project course and want to teach about this somehow. But twice two hours is way to short. Maybe I'm trying to put two much learning in too little.
