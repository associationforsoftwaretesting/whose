---
title: "White Box Techniques"
date: 2015-04-10T17:08:00+00:00
lastmod: 2015-04-10T17:08:00+00:00
draft: false
images: []
weight: 040
toc: true
---

## Definition:

White Box Testing is a general label applied to design techniques used when the tester/test designer knows and takes into account the software's code, design, and other aspects of its structure.
This is not a properly a skill.
It is a label for techniques that incorporate many skills within the broader skill of designing meaningful tests.

## A context where I used this skill:

When I was a developer-‐‑tester (now called an Agile developer), I iteratively built design, code, and test information.
Yes I did the code and then tested, so I was not pure Agile TDD, but every line of code had tests for it.
This gave me statement coverage.

Also, each "IF" test had a truth table from which I build more test cases.
This gave me decision and branch coverage.
Well with the coverage based white box testing, my code had few bugs than other developers and I was invited back during system integration to "help" when other developers were not (I had job security).

## How I'd recommend someone learn this skill:

Understand what white box testing means as a technique, and then learn how to either read or write code.
Here are the classic white box code coverage techniques:.

* Statement Testing
* Branch Testing
* Decision Testing
* Branch Condition Testing
* Branch Condition Combination Testing
* Modified Condition Decision Coverage (MCDC) Testing
* Data Flow Testing

Each of these have coverage measures associated with them.
There are subtle little problems in coverage measurement and a coverage can "mislead" and miss bugs.
For example consider the line of code.

x = y/z

I can test this with setting y = 4 and z = 2.
My answer is 2 (this is the oracle), but consider there is still a bug here possibly.
What if I set z = 0? What does the computer do with something that is math undefined? Is there a "IF" test or some language feature to protect z from being zero? So there is more to this skill-‐‑technique than just coverage.


## Additional resources:

["Software Test Attacks to Break Embedded and Mobile Software"](http://www.amazon.com/Software-Embedded-Innovations-Engineering-Development/dp/1466575301), Jon Hagar, 2013 Ch 2 developer attacks, CRC press


By: Peter Walen

