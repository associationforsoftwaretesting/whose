Black Box Techniques
====================

## Definition:

Black box testing is a general label applied to design techniques used when the tester/test designer does not know or does not take into account, the software\'s code, design, or other aspects of its structure.


## A context where I used this skill:

Pretty much any test effort where I was not directly involved in development, I was doing some form of black box testing.

In one case, I was testing rockets.
We defined scenarios based on requirements and expected system-‐‑software usage.
The rocket would count down, lift off, fly up and away.
This was our starting black box usage scenario.
We ran this test over and over at first.
Then we started to test \"off normal\" scenarios to test the boundary cases.
We tested a countdown that stop just before T=0.
Tested a countdown that stop right at T=0.
These were boundaries where we wanted to see how the software-‐‑system worked in different scenarios.
We of course had many other cases.
We once counted up how many \"normal\" and \"off normal\" black box scenario cases we had tests for.
About 60% of the testers were off normal (stress cases) and another 20% were \"normal\" but at a boundary.
This means only 20 were regular \"normal\" tests.
We were push the software, even in the black box, to situations that might not be normal, but that the software should handle without bugs.


## How I\'d recommend someone learn this skill:

Since the skill is made up of a variety of techniques, as tester must learn the patterns needed to implement the technique.
To do this one must start with the \"classic\" industry recognized names of these, which include:.

➔ Equivalence partitioning
➔ Boundary value analysis
➔ Decision table testing
➔ Classification tree method
➔ Syntax testing
➔ Combinatorial test design techniques
➔ Cause-‐‑effect graphing
➔ State transition testing
➔ Scenario testing
➔ Random testing

A student of black box testing will recognize there are other names and variations for black box test techniques, but the names given here are the basics.
To learn the skill/technique a tester must know the name, and then must be able to do the following:.

➔ recognize when the test problem fits a technique
➔ either know the technique pattern or how to find the details of the pattern to be able to apply the technique (note: tools may be needed to
support a technique)
➔ once the pattern can be practiced, the tester must be able to define the test design including: a plan, the inputs, the environment of the
test, the activities of the test, and be able to judge (oracle) the test.

If a tester is doing scripted testing, the design happens then the testing, but if one is doing exploratory testing, the testing and design with information gathering happen in real time.
To learn skill of black box test design and associated techniques, one must practice, practice, and practice as well as being able to look the pattern details up when needed.

## Additional resources:

[BBST classes](http://www.associationforsoftwaretesting.org/training/courses/){.external .text}
[The Domain Testing Workbook](http://contextdrivenpress.com/){.external .text} -‐‑ Kaner etal -‐‑ (this is a comprehensive \"how to\" with skillbuilding learning workbook)

By: Jon Hagar

Return to [Test Design](Test_Design.html?title=Test_Design "Test Design")
Return to [Main\_Page](Main_Page.html?title=Main_Page "Main Page")
