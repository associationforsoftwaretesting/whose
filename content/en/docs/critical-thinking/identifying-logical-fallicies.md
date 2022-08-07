---
title: "Identifying Logical Fallicies"
date: 2015-04-10T16:37:00+00:00
lastmod: 2015-04-10T16:38:00+00:00
draft: false
images: []
weight: 030
toc: true
---

## Definition:

Understanding when the conclusions someone gives at the end of an appeal are not really supported by any claims they have made.

## A context where I used this skill:

A customer of mine in Chicago outsourced a ton of testing to an offshore contract testing organization.
In order to exercise changes to core business rules the outsourced testers agreed to include one positive test and one negative test for each changed rule.
Both organizations believed this to be reasonably complete testing of the changed logic.

The outsource testing team diligently completed the work and ensured that one positive and one negative test was run, and passed against every changed business rule.
The completed application went into a pilot implementation during which very high failure rates (over double that of similar previous projects) were encountered when executing transactions using the revised rules.

I studied the situation (test planning, design, implementation and reporting).
I determined that both organizations were operating under the logical fallacy that one positive and one negative test would thoroughly exercise each changed business rules.
Several negative tests would have been required for almost every changed business rule I examined.

Even the simplest case of a business rule with two Boolean conditions (A and B) would have required at least one positive test and three negative tests to basically exercise the business logic (this is often called full condition coverage).
(note this can be demonstrated by using Demorgan's rule in Boolean algebra).

| A | B |          |
|---|---|----------|
| T | T | Positive |
| T | F | Negative |
| F | T | Negative |
| F | F | Negative |

## How I'd recommend someone learn this skill:

First study logical fallacies, then pick up any major newspaper, turn to the editorial section, and look for them.
Another related thing to look for is inconsistency of rhetoric ------ when the person the paper likes does something, it is "leadership", while when the opposition does it, it is "manipulation."
(Another example: "lies" vs "mistakes", "bad word choice", and "misunderstood.")

If you are really motivated, get a copy of [Logic and Rational Thought](http://www.amazon.com/Logic-Rational-Thought-Frank-Harrison/dp/0314668144) by Harrison and go through the books section on logical fallacies.
It is exceptional and include exercises.
(Robert Sabourin's example about is close to what Harrison refers to as the fallacy of the false dilemma.)

## Additional resources:

* [Master List of Logical Fallacies](http://utminers.utep.edu/omwilliamson/ENGL1311/fallacies.htm)
* [Logic and Rational Thought](http://www.amazon.com/Logic-Rational-Thought-Frank-Harrison/dp/0314668144), Frank Harrison


By: Robert Sabourin

