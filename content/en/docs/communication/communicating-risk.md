---
title: "Communicating Risk"
date: 2014-11-20T16:31:00+00:00
lastmod: 2014-11-20T16:31:00+00:00
draft: false
images: []
weight: 030
toc: true
---

## Definition:

Eloquence combines several skills, but it includes knowing how to communicate to the audience in a way that it can be heard.


## A context where I used this skill:

Years ago doing programming on a project to generate insurance packets to customers.
If we didn't hit a magical deadline, the packets would be 'late', which had the perception, at least, of incredible pain \-- people with insurance without the documentation of what the benefits were or legal proof.
Yes, I was writing the code, and also testing my own code.

The alternative to getting the code out was to hire an army of interns to copy values from spreadsheets into MS Word, then export to PDF.
Or something.
Before the process was automated, the company had done something manually, but exactly what had been lost to oral history and mysticism.
Like so many other business processes, the perceived choices were "have the automated code done by (date) or (mumble something horrible about how we needed to have it done by the date.)

And, of course, the requirements were late.
Changes came in late to the system.
The programming was done by Matt, who, while not a junior programmer, was new to this system, and working on it part-time, in addition to other responsibilities \.
until it became obvious that we had a schedule problem.
The code was mostly done, it was just buggy.
How buggy, we didn't know, as my testing was an expanding spiral around the code I had changed.

Suddenly, with a date problem, IT management was talking to the line of business management.
The line of business management explained that it was "okay" to "take a few risks", and I was asked if we could go-live Friday.
How could I answer that? I didn't really know how buggy the thing was.

What I did know is that Line of business management wasn't in a position to understand the risks they were taking.
If the software had a bug in a for-loop, it might send the same packet to every person.
An off-by-one error could mean packets were sent to the wrong house - so personal health information from one family would "cross streams" to another family, a legal violation.
A merge error might mean that families got documents that looked correct, but the actual information on them, the deductible, copay, etc, was wrong.
If the copay or deductible was too low on the packet, then the person would expect this coverage at the doctor's office, and we'd be liable to complaints and possible legal battles.
And say the code has any of these bugs - how much effort would it take to change, resubmit, and recreate correct packets? What would the cost be to reprint and reship?.

It turned out quite a bit.

What I endeavored to do was to move the conversation past "We are willing to take some risk here" into the realm of what those risks actually entailed.

All of a sudden management wanted to go back and look at their legal obligations to ship packets, and I got a couple of more weeks for my schedule.

## How I'd recommend someone learn this skill:

Offer to the be point person in making the ship decision.
If you can't do that, try to be in the room.
If your organization ships so often, and rollback is so easy, that you don't have those sorts of meetings, that's fine - work on requirements definition or the portfolio.
At the portfolio level, every decision on what to spend time is a decision to not spend time on a hundred other things, and someone is eloquently arguing for the projects that win.
Study that person.
Move from studying to experimenting, and do it consciously.


## Additional resources:

["Crucial Conversations: Tools for Talking When Stakes are High"](http://www.amazon.com/Crucial-Conversations-Talking-Stakes-Second/dp/0071771328/){.external
.text} by Patterson et al talks about how to deal with defensive and high pressure situations
"How To Win Friends and Influence People" by Dale Carnegie (get the original, non-update version), talks about how to send a message that will resonate with your audience


By: Matt Heusser

