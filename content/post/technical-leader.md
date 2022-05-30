+++
author = "Fabian Gilson"
title = "Good coding practices need an advocate inside the team (or it won't work)"
date = "2022-05-30"
description = "How hard it is to convince a team to write good code"
tags = [
    "teaching",
    "research",
    "code quality",
    "technology"
]
+++

A few years ago, we looked into how teams deal with the technical debt in a software engineering project course (DOI to [paper](https://doi.org/10.1145/3387906.3388624)). One of the main takeaway from the focus group that followed an extensive data analysis (of the evolution of the quality of the code of 8 teams) and a survey (with 25 responses, being 40-ish % of the class) is that the adoption of clean code practices seem to be strongly influenced by a charismatic and engaged _"team leader"_. From a literature review (to appear soon at EASE, preprint [here](https://gitlab.com/mde4asd/hybrid-software-testing-reproduction-pkg)), we observed that the same pattern, i.e. the need for strong advocates in teams, exist for automated software testing in industry context. From these two studies, I believe that _"old"_ XP advocates actually got it right and we have failed miserably to listen to them. Therefore, we felt into the same trap as before, i.e. process rigidity and putting the process before the people (and when I say "we", I think education and industry).

Let's give a bit more context on both studies first.

## Code quality in a software engineering course

Briefly, students are put in teams of 6 to 8 to work over a full year (well, 24 study weeks in Aotearoa New Zealand, which is rather short, actually). They work in a Scrum environment (with quite a few adaptations to make it work in a part-time work) and are carefully mentored (and monitored) by an extensive teaching team. The overall goal is to develop a software product in 6 or 7 iterations (i.e. _sprints_) and make sure students get a practical hand on software development practices, team-based work, continuous integration and deployment, code reviews and a bit of requirement engineering. If you want more details, just check section 4 of referenced paper above if you want more details.

During that instance of the course (in 2019), we introduced a static analysis tool and encouraged students to use it (it was part of their CI pipeline). We also explicitly commented on their delivered product after each iteration, including comments on the code quality and analysis reports (from SonarQube). Still, very few teams used it regularly and the tipping point seemed to be linked to one member of the team, usually recognised as a technical guru or leader. It didn't really matter how they were implementing this quality assurance process (e.g., in code reviews, co-location or pair-programming sessions), but the result seemed strongly linked on individuals driving the team on that aspect. And certainly not the teaching staff (the frequent feedback seemed to be outweighed by time pressure).

## Automated testing practices in the industry

In that systematic literature review (my first published one, how boring to carry, but in the end, I'm happy we did it), we looked at how automated testing for unit (of code) and (user) acceptance levels could share common methodological patterns (or not). This research was conducted in two phases: 1) a mapping study on automated unit and acceptance testing (i.e. looking at the broader scope); 2) a literature review focusing on papers with an industry focus. In the end, among published papers, Test-Driven Development (TDD) and Model-Based Testing (both from automated generation or as _"drivers"_ for testing, MBT) were the most popular techniques. Still, for developer teams to put the needed effort into software testing (in general), most researchers working with the industry reported that these teams had an **advocate inside** development teams (or a dedicated quality assurance **person**). It's also worth noting that benefices from TDD or MBT was not linked to how well teams were following the method to the letter, but simply linked to the mindset induced by the testing practice.

## People implement processes, actual processes don't matter as much

From these two pieces of research, I strongly believe that we are currently putting way too much importance to processes and not enough to people. There is a whole research domain of human factors in software engineering. There are also lots of advocates (mostly _XPers_ from the early ages) preaching to come back to ensemble thinking and programming where we need to acknowledge that what we do cannot be created in a _Taylorist_ way, sadly what the Jira (or Monday) generation of leaders is pushing for. As software engineering researchers (and industry), we keep developing more tools and metrics to support software development, but we also drive developers apart more and more (see how bots are becoming a thing in open source development). We probably need now to invest into how to build better working environments for developers to find their own way of implementing a particular process. The way that make sense to them. This is what we observe in a non-empirical way for now in our project course (but there are plans to look into this soon): **teams that understand the fundamentals of software development processes, adapt one and make it their own, tailored to their team culture and dynamics, produce the best results**. Both in terms of software products, but more importantly, in terms of practical experience. And this, usually needs at least one _"technical or methodological leader"_ **part of the team**.