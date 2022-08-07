---
title: "Quick Attacks"
date: 2014-11-02T19:16:00+00:00
lastmod: 2014-11-02T19:31:00+00:00
draft: false
images: []
weight: 020
toc: true
---

## Definition:

Quick attacks are a collection of methods that you can use to begin testing immediately, without much understanding of what software is supposed to do or the underlying business requirements.
Most quick attacks are broad and shallow, based more on the commonly-known ways a platform can fail than any knowledge of the underlying application.
Examples of quick attacks include putting numbers too large, too small, or too precise in text fields, entering numbers where text is expected, and so on \-- forcing what seems like exceptions to the usual process to see if the programmer wrote code to handle those exceptions.

## A context where I used this skill:

I came into a test as a consulting software tester on day one; there was some concern if I was going to be a little \.
academic.
I believe the request (mostly from programmers, not testers) was for "Doing of testing with coaching as a bonus, not the other way around.
" It's a fine thing to ask, and I accepted the job, and the rate was fine \-- I am not complaining.
I will admit a little anxiety.
So we start on day one.
The application was complex; the documentation was slim to none.
The little documentation that did exist was trapped in a quality management system and consisted of step-by-step directions - not an overview of what the system was or how it worked.
Most of the teams legacy applications worked by reading from a database (or a flat file) and doing some processing; the challenge of the day was to take those service, wrap them, and allow customer service to make hand changes by way of a GUI, so I tried quick attacks - sending in data through the GUI that was horribly wrong, or doing things in a different order than the programmer expected.
I found a moderately large defect by lunch that was a reasonable activity for a customer service person, and would have caused significant downstream problems had the bug survived in the wild.
Come to think of it, that's a decent build credibility story, isn't it?.

## How I'd recommend someone learn this skill:

[Hands On Keyboard Quick Attacks](http://itknowledgeexchange.techtarget.com/software-quality/teaching-quick-attacks/){.external.text} walks the reader through several exercises.
It's a common place for me to start teaching testing and provides other valuable links, worth mentioning here, like Elisabeth Hendrickson's \[<http://testobsessed.com/wp-content/uploads/2011/04/testheuristicscheatsheetv1.pdf> Testing Cheat Sheet\] and the article [Ten Quick Attacks For Web Based Software](http://searchsoftwarequality.techtarget.com/tip/Ten-quick-attacks-for-web-based-software){.external.text} along with a link to [Triangle TestOMeter](http://www.testinggeek.com/software-testing-testometer-triangle-test){.external.text} .

## Additional resources:

[BBST Test Design](http://www.testingeducation.org/BBST/testdesign/){.external.text} , specifically lecture 2
[How To Break Web Software](http://www.amazon.com/How-Break-Web-Software-Applications/dp/0321369440){.external.text} , by James Whittaker

By: Matt Heusser

