---
title: "Identifying Combinatorial Explosion"
date: 2014-11-20T15:00:00+00:00
lastmod: 2014-11-20T15:01:00+00:00
draft: false
images: []
weight: 060
toc: true
---

## Definition:

The combinatorial explosion is the list of potential test ideas based on some model of the system.
Combination testing is about picking a few tests that can teach us what we need to know about the space of combinations of these variables.

## A context where I used this skill:

Recently, while working on a project that involved a table change to add new languages available as "preferred languages" in a registration module for a shopping system we saw several potential problems.
The test group was repeatedly told that there were no code changes made, testing should be fairly easy.
On examining the number of areas where that table was referenced simply for registration and profile maintenance it seemed more complex.
It was invoked from a desktop webpage, a mainframe green screen (user customer service staff) and mobile applications on iOS and Android.
Given the number of languages being added and the number of forms, emails and other impacted customer facing integration points, I mapped the existing and new language combinations across the application.
There were four (4) new languages being added to the original two (2).
This, given the other interacting variables gave a potential of 366 combinations of variables and resulting potential test instances for the web UI and green screen modules alone.
Mobile apps had an additional 120 variable combinations to consider.
By evaluating the combinations, I was able to reduce the desktop tests to 41 and mobile tests to 14.
These found over 20 bugs that would prevent the software from working.
Two more bugs were found after deployment in areas I had no idea were touched by the change.

## How I'd recommend someone learn this skill:

I found the ideas from Cem Kaner (here: [Examples of Combination (Multi-Variable) Testing)](http://www.testingeducation.org/k04/ComboExamples.htm) helpful in understanding how to do this and explain it to others.

## Additional resources:

[All Pairs](http://www.developsense.com/pairwiseTesting.html)

By: Pete Walen

