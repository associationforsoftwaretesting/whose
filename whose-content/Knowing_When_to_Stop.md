Knowing When to Stop
====================

## Definition:

The testers ability to deliberately end a testing effort based on one or more completion criteria, knowing that their testing was good enough and that the value of additional testing is less than the value of some other alternate course of action.

## A context where I used this skill:

One example of when the skill of \"Knowing when to stop\" testing was critical was the Rendez-Vous project.
Rendez-Vous was a fixed delivery date business critical project.
The Rendez-Vous product was used for patient scheduling at medical clinics.
The product was delivered as shrink wrap desktop software.
Rendez-Vous was developed using a blend of Visual C++ and Delphi technologies for a Windows based PC platform.
We decided that the testing would be complete when we could walk through a set of twenty seven specific usage scenarios with defined data having resulting system behaviour validated by a group of selected subject matter experts.

Another example of using the skill of \"knowing when to stop\" testing was in bug confirmation testing.
Jason, a tester in my team, was assigned the job of confirming developer bug fixes.
Jason was concerned that programmers had accidentally broken something else when fixing the bug.
The product under test was a desktop security suite running on Windows pcs.
The bug confirmation testing took place frequently during the system test effort of a project following a waterfall like software development lifecycle model.
Jason confirmed bugs with several steps:

1. Demonstrate bug existed in previous build
2. Try same steps on the new build
3. Imagine a scenario the user would experience which would have encountered the bug
4. Demonstrate that the imagined scenario works acceptably
5. Vary the steps and data in the scenario confirming acceptable behaviour
6. Continue the perturbations until the scenario becomes absurd in the eyes of prospective users

Jason learned about absurd usage perturbations by discussing the bug confirmation scenarios with members of the support department, training department and user community.

## How I\'d recommend someone learn this skill:

I often coach testers about how to \"know When to Stop\" testing.
I start with making sure the testers have a good solid understanding of the notion of coverage.
I ask them to identify at least three different coverage notions associated with their project and a good article I point them to is by Cem Kaner entitled [\"Negligence and Testing Coverage\"](http://kaner.com/pdfs/negligence_and_testing_coverage.pdf){.external.text} which discusses over one hundred different ways to look at test coverage.
I ask testers to learn about goals and awareness of achieving them.
I find the writings of Steve Covey, especially his book the \"Seven Habits of Highly Effective People\", very helpful.
The first habit Steve Covey teaches is begin with the end in mind, first things first.
I ask testers to look at some important examples from previous projects with different exit criteria for testing.
I point them to an [Acceptance Testing Case Study and a Combinations Testing Case Study.](http://www.google.com/url?q=http%3A%2F%2Fwww.amibugshare.com%2Fcase_studies%2FCase_Study_Acceptance_Testing.zip&sa=D&sntz=1&usg=AFQjCNHULnPvHth84rL1KiCE1fPLttY3vA){.external.text}
I ask testers to learn about eliciting notions of what is good enough, or what does \"Done\" means.
I encourage testers to interview project stakeholders and to review examples of good enough quality from past projects.
I ask testers to learn about bugs found in the field which had to be corrected from previous projects.

I ask testers to come up with a prioritization strategy for test objectives on their project.
I ask testers to review this with stakeholders to make sure it is acceptable to them and to get feedback.

I ask testers to learn about challenging their assumptions pointing them to references such as the [Rapid Testing](http://www.satisfice.com/info_rst.shtml){.external .text} course by James Bach and Michael Bolton.
I ask testers to participate in project retrospectives in which they can see how other testers decided they had done enough testing.

## Additional resources:

[I am a Bug](http://www.amazon.com/I-am-Bug-Robert-Sabourin/dp/0968577407/ref=sr_1_1?ie=UTF8&qid=1416496046&sr=8-1&keywords=i+am+a+bug){.external
.text} by Robert Sabourin describes that \"\... we know we are finished when the bugs that are left are bugs we can live with at least for now\...\"
[When Do We Stop A Test](http://www.developsense.com/blog/2009/09/when-do-we-stop-test/){.external .text}, a blog post by Michael Bolton

By: Robert Sabourin

Return to [Time\_Management](Time_Management.html?title=Time_Management "Time Management")
Return to [Main\_Page](Main_Page.html?title=Main_Page "Main Page")
