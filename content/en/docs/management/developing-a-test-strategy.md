---
title: "Developing a Test Strategy"
date: 2015-04-24T15:54:00+00:00
lastmod: 2015-04-26T01:45:00+00:00
draft: false
images: []
weight: 010
toc: true
---

## Definition:


Selecting test methodologies based on available resources that will be applied within the context of a specific project.

-   The development of testing strategy for a project starts with the mission, that defines the goal of testing activities for a specific project stage, and identifying the risks for this specific project stage.
-   The next step is to analyse all available resources: people skills, tools, and time. The resources will be driving selection of test methodologies.
-   The final step is to discuss the strategy with stakeholders, and revisit the strategy when the project requirements, dates or resources change.

## A context where I used this skill:

I used this skill continuously as a Test/QA Lead and QA Manager.

Here is an example:

I was working in a financial services company, and we started developing a new web product.
This product was new for us but not unique on the market, and the business stakeholders needed some feedback from customers whether they will be using it.
The goal for our product development team was to create a working product ASAP, with the minimal, but fully working features and the unique interface.
Differentiating factor for this product was the usability and attractive interface, on top of functioning features.
This product was intended for two-three clients.

The context analysis:

1. Project stage: development of robust, while non-scalable product (in prototype mode, so that features could be easily tweaked). This product was intended for 2-3 clients.
2. Process: agile development, discovering requirements as we go. Such process is acceptable with the brand new products, which are entering uncharted waters.
3. Project risks: building a product with financial features which show wrong data, non-intuitive interface, too late to market.
4. Available resources: one tester, several developers, and one business analyst on the team. Whole company that is curious to learn about new product.

The strategy:

1. A lot of exploratory testing: new frequently changing functions and interface, defined formulas for financial calculations. This tester was an expert in ET, and such testing provided most timely feedback to programmers.
2. A choice to not use test automation. Reason: the product was not validated with customers, and was built in prototype mode. Both these reasons indicated that the team was developing a throwaway code and the project could end after initial validation with customers.
3. A choice to not conduct load testing. Reason: the product was built for limited amount of users.
4. A choice to limit testing to a specific browser version. This strategy was discussed with stakeholders, who agreed to such limitation in order to cut on time to market. Business announced this browser version to the intended customers, who were preselected for the initial feedback.
5. The dilemma was with validating usability. To reiterate: usability was major differentiating factor for this product, it expected to set us aside from competitors. One tester on a team, however experienced, could form a biased opinion on product usability. The same bias was observed with programmers, who didn\'t notice potential \"hard to use\" features due to their own preferences. The strategy was to employ \'focus groups\' throughout the company, that were composed of company employees who wanted to have a first peek on the brand new product. The special exersizes were developed for \'focus groups\' in order to test the product usability in a friendly, non-stressful environment, simultaneously allowing participants to learn the product. Such exersizes were created in a way that allowed development team to observe how new users interact with the product, and change interface based on the observation and feedback.
6. During the course of development, the new \'pioneer\' customer was added to the list. It turned out that the specific browser version we originally selected was incompatible with this customer\'s operating system. The decision was to add another browser version to be tested.
7. When the project was in its\' final pre-production stage, programmers added several \'nice to have\' features, which significantly added to complexity of the code. As a result, the amount of new bugs drastically increased. Tester initiated the conversation where it was decided to shut down several features in order to preserve the robustness of the working code.

## How I\'d recommend someone learn this skill:

Learning this skill involves integrity and critical thinking, and sharpens with experience.
Here are some principles:.

-   You have to be honest to yourself, to your team and your management that there is always definite amount of resources available. To reiterate, resources include people skills, tools and time. There is a possibility that people on your team want to learn a new skill/tool during the project; in this case, you need to a) add a learning curve and b) assign a coach/reviewer to this person. Both activities add to the time.

-   You have to be very critical when identifying and analyzing the project risks. For that, you have to know your stakeholders, their needs for quality at this specific project stage, and which risks are critical for project success at each stage. For example, R&D project stage has entirely different risks than Release into Production project stage.

-   You have to learn pros and cons (limitations) of each test methodology: being it test automation, exploratory testing, testing in production, unit testing/TDD, etc.

-   You have to learn pros and cons (limitations) of various test tools for short term and long term goals, and be brave enough to switch to another method, if the tool doesn\'t fulfill your project goals.

-   You need to revisit your strategy often, as the project context changes continuously and unpredictably.

## Additional resources:


[BBST Foundations Strategy Video 1](http://www.testingeducation.org/BBST/foundations/Lecture2aFoundations2010.mp4){.external
.text}
[BBST Foundations Strategy Video 2](http://www.testingeducation.org/BBST/foundations/Lecture2bFoundations2010.mp4){.external
.text}
[Heuristic Test Strategy Model by James Bach](http://www.satisfice.com/tools/htsm.pdf){.external .text}

By: Anna Royzman

