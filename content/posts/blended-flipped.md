+++
author = "Fabian Gilson"
title = "Moving to a partial flipped classroom"
date = "2021-07-30"
description = "Random thoughts on moving to a partial flipped classroom teaching style"
tags = [
    "teaching",
    "flipped-classroom",
]
+++

This year I tried something _"revolutionary"_: asking my third year students to read some material before coming to class. Well, I must admit, this has had mixed success and here is why.

TL;DR. I'll keep doing it ;)

## The context

Lectures are 50 minutes long, twice a week. The students are third year software engineering, computer science and game design students. They all went through at least a couple of programming courses and one introductory software engineering course (e.g., OO concepts, major UML diagrams, basic architectural patterns, basics of software engineering practices like the usual software development phases and what they mean). There are officially approximately 100 students enrolled, but after a couple of weeks, 40-60% or so were showing up regularly in-person, another 10-ish watching live on the internet (the joy of students' attendance at uni with live broadcast and recording of lectures).

## The principles

Before each class, students were asked to read some grey literature articles (e.g., blog posts or technical non-peer reviewed articles). The following lecture, we would make some _"breakout"_ groups where students discuss about their main takeways with their peers and share with the class or we would have some quizzes over _Kahoot!_. This preparation work would take around 30 minutes at most (time to read and time to summarise their takeaways).

### Examples

As an example, for the lecture on _Software architecture 101_, these were the preparation readings:

- Martin Fowler's [You aren't gonna need it](https://martinfowler.com/bliki/Yagni.html)
- Sven Gregori's [``Good Code Documents Itself'' And Other Hilarious Jokes You Shouldn’t Tell Yourself](https://hackaday.com/2019/03/05/good-code-documents-itself-and-other-hilarious-jokes-you-shouldnt-tell-yourself/)
- Andreas Zwinkau's [3 ideas How to Communicate Your Architecture](http://beza1e1.tuxen.de/communicate_architecture.html)

And, during the lecture, on top of some more _"conventional"_ exercises, there was a _Kahoot!_ with questions like:

- _Getters and Setters do not need documentation?_
- _YAGNI stands for?_

In another lecture about ethics, students were required to look at the University's code of conduct (including academic integrity), articles about [Timnit Gebru](https://www.wired.com/story/google-timnit-gebru-ai-what-really-happened/) and the [ACM code of ethics](https://ethics.acm.org/code-of-ethics/software-engineering-code/) and we would reflect in class about the content of these documents (both in breakout groups and as a class).

### Not an assessment per se, but still required work

This preparation work had 0 marks awarded and no other _incentive_ than _"If you don't do it, you won't be able to participate to the activities properly"_. Still students knew that all of this prep work was part of examinable material for the final exam (10 marks our of 100 for an exam that is worth 60% of the final marks - I know, I need to change this, but this will be another story about balancing assessment items that I need to discuss later - ). In other cases, there were also videos, such as GeePaw Hill's [TDD underplayed premises](https://www.geepawhill.org/2018/01/18/five-underplayed-premises-of-tdd-2/).

Also, students had fewer assessment items over the semester, so students had time to spend on this preparation work before every lecture.

## The engagement

Did it work or not? Well, some of it...

### The bad

Let's make it clear now, I got angry one time because a dozen only looked at the preparation work before coming in class once. This was probably in week 3 or so and assignments in other courses started to kick in on top of student life stuff (read, parties). This happened in class. I apologised the next lecture ¯\\_(ツ)_/¯

Class reps also reported that _"All students cannot read so well and a 10 minute blog can be long."_ This made me angry, but not in front of them this time. Hearing that what is supposed to be the future elite of the country cannot spend 10 minutes to read some piece of writing made me laugh, cry, laugh, cry again and then take a beer to forget about my job for a minute.

Others struggled with the jargon used (I agree that using Kent Beck's [Basket of options](https://medium.com/@kentbeck_7670/decisions-decisions-or-why-baskets-of-options-dominate-9ac63658b593) to start the year may have discouraged a few straight away, still one of my favourite). So at leasst, I need to look after the order and difficulty of the prep work I ask students to do.

### The good

I received positive feedback from some students (verbably and in my teaching evaluation) that really enjoyed going through the preparation material. Their main arguments were:

- this additional material gives a broader overview of software engineering, outside an academic context;
- it connects the course material to industry / real-world examples;
- some students missed this preparation work in the second part of the course (that I don't teach), made me feel good (we need that sometimes).

And, yeah, no need to say that students liked the (at least weekly) _Kahoot!_.

### The funny

_Never ask about something directly..._

I gauged this thing in two different surveys: one teaching evaluation with no specific questions about this preparation work and one course evaluation with a specific question about it. In the teaching survey, some students mentionned that the preparation material and the readings I asked them to go through were really helpful (in their free-text comments). But when asked specifically about it, results were more mixed with approx 18% of students finding this prep work not _"insightful"_ (the wording I used), 36% were neutral and the remaining 43% were positive. Still, it isn't a disaster, I was actually expecting worst results than an average 3.3 out of 5 for that question (likert scale).

## So, what now?

From a teaching point of view, in a third year undergrad course, I'm expecting students to be able to tackle more complex pieces of writing. Still this assumption revealed a bit too strong. There was an exam question about the main message from Kent Beck's aforementioned blog post, failed by a large chunk of the class. So in clear, my advice would be to **take the time in class to decipher some more complex pieces of writing**.

Another thing is to probably **incentivize (or better, reward) the preparation work**. It goes against most of my personal principles, but some students seem to need that to actually get into it, and not only _"bad"_ or _"lazy"_ ones. It's sad, but understandable.

Another very personal reflection for me is that coupling my lecture material to these external readings forces me to **keep me up-to-date** (yep, software engineering is no algebra, it keeps changing). It also (hopefully) inspires students to keep themselves updated by spending more valuable time online, I mean on something else than Reddit or Instagram, but actually learning new stuff or making them reflect on our discipline.
