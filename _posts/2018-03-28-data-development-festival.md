---
title: Back from Data for Development Festival
image: assets/posts/2018-03-28-mind-the-gaps-stand.jpg
tags:
- presentation
- bristol
---

Noemie and I (Thomas) were at the first instalment of
[Data for Development Festival][] in Bristol from March 21st to March 23rd.

<!--more-->

# What is Data for Development Festival?

It is the first instalment of an event produced by the
[Global Partnership for Sustainable Development Data][].
This organisation was created in 2015 to bring a data driven approach to the [sustainable development goals][] adopted during the 70th session of the United Nations General Assembly.
We can find _health_, _energy_, _inequalities_, _cities_ and _gender equality_ among these goals.

The Festival was a 3 days event with an international audience, panels, presentations and projects showcase.

We were present at the event as part of the _projects showcase_.
We [applied to the festival]({ post_url 2018-02-06-opendata-festival-proposal %}) back in February.

{% include figure.html src="assets/posts/2018-03-28-data-dive.jpg" alt="The Data Dive session to surface interesting things out of Bristol datasets" %}


# Project Showcase Setup

The format we were offered was 90 minutes on a standup booth, with a table and a large screen.

We thought of following a simple approach to present the project at the Festival: **using the project website as a main material**.

We redesigned the landing page of the website with this idea in mind.
We used larger fonts, a responsive layout and more comprehensive texts for newcomers.

{% include figure.html src="assets/posts/2018-03-28-mind-the-gaps-stand.jpg" %}

We opened a web browser _private session_ in full screen and had a few tabs open in advance:

- the [product page](/)
- the [research page][] — the content which was formerly the landing page
- [Bristol survey question](/surveys/uk/bristol/) to highlight the nature of the questions
- a [daily retrospective example]({% post_url 2018-02-14-retrospective %})
- the [toolbox schema]({% post_url 2018-02-08-toolbox %})

We ended up disposing sticky notes and markers on the table, to enable hand written contributions.
We used them to write down our email address so as people could take them in picture with their smartphones.

We will see if phone-taken pictures of email addresses generate more leads than regular business cards.

On a side note, we even contributed some code to the open source [wawoff2][] project.
We wanted to embed web fonts and felt we could help speed up the conversion process by removing one step. [Contribution accepted](https://github.com/fontello/wawoff2/pull/3)!


# Insights and Lessons Learnt

We did not know much what to expect out of the event.
We came back happy of the **positive reinforcements** we got from the various interactions.


## Methodology

The process of customisation of the survey came up in nearly all of the conversations.
We were asked _how we did it_ and _how it can be replicated_.
In which case, showing the [research page][] was a relevant move.
We see this as a prompt **to develop the writing of the interview guide**.

Our conversations with participants confirmed we would need
to develop our capacity building: **interviewers should as much as possible be from communities surveyed**. How can we help them contextualise the _interview guide_ and be non-leading, non-biased, equipped to answer questions?

The _capacity building_ can be related to the tehcnical implementation itself.
Students could run a survey without a prime ability to set it up on their own.
In addition to a **research methology**, we could consider **delivering a runbook** to bootstrap the project in various conditions — from a minimal setup to hosting the data on your own.

We are open on finding financial resources to produce these documents and/or to train people on the field to be autonomous.


# Biases and inclusivity

We have tried to design an inclusive process and to make Mind the Gaps bias-free.

Some festival participants happened to think the project would be a good system to address people that are usually not reached by online surveys.
It will be important to **emphasize the tradeoffs of each method** (face to face interview, online questionnaire, group-based approach) so as they are chosen for the good reasons, for their qualities.

Bias is also something which can be **induced by field work**, by ethnographic researchers.
The cultural context is something to be aware of.
For example, men would not go as easily up to women in some arabic countries. In some neighbourhoods, our clothing would create a divide between us and the respondants.
**Diversity of interviewers is required in order to achieve representative results**.


# More than social inequalities

There is an opportunity to generate data about various forms of marginalisation
because they are not well addressed by existing statistics.

This is especially true when they are endangered or put at risk to speak about the reason of their marginalisation (sexual preferences, religion, ethnic origins, etc.).


# Next steps

Many asked us <q>what are your next steps?</q>.
We replied we wanted to develop a _survey v2_ (more useable UI, better data structure), fleshing out questions, test with community organisations, visual insights and capacity building.

We were also asked if we would be interested in bringing _Mind the Gaps_ in different languages, in rural areas and in developping countries.
It is something we would be happy to do. It would be a case of making the system properly reusable.

Another question was if we were going to provide help with the data analysis?
There are 2 answers to that:

1. providing human readable analytics would definitely be part of the job
2. with organisations like [DataKind][], it would be interesting to submit _Mind the Gaps_

The [Humanitarian Exchange Language][] could be a sensible move to add SDG metadata to flag questions and answers relative to their development.<br>
It would make a good case to submit the project to the Global Partnership Fellowship programme.

{% include figure.html src="assets/posts/2018-03-28-bullshit-bingo.jpg" alt="The official buzzword bingo sheet — kindly provided by the Festival itself." %}


# Notes on the Festival

We enjoyed the Festival was not Western centric.
A lot of do-ers had good insights of the field whereas panels and presentations were better at addressing the organisation and financing side of things.

> Pick our brain, not our pockets.

We spotted the [risk paradox with regards to funding](http://www.data4sdgs.org/news/making-case-more-and-better-financing-data).
Grants and fundings are allocation of moneys which originqte from private donors (wealthy persons, foundations, big corps special funds).
Donors want the outcomes to be measurable. Fuzzy/research-y projects are harder to fund as they cannot be measured in such ways.
Producing knowledge and guides is not as much in the scope of the grants.

{% include figure.html src="assets/posts/2018-03-28-unicode-is-hard.jpg" src="Unicode is hard." %}

{% include figure.html src="assets/posts/2018-03-28-packing-up.jpg" alt="On our way to our next destination after the Festival!" %}


[Data for Development Festival]: http://www.data4sdgs.org/news/data-development-festival
[Global Partnership for Sustainable Development Data]: http://www.data4sdgs.org
[United Nations Millenium Development Goals]: https://www.un.org/millenniumgoals/global.shtml
[sustainable development goals]: https://www.un.org/sustainabledevelopment/sustainable-development-goals/
[wawoff2]: https://github.com/fontello/wawoff2
[research page]: /research/
[DataKind]: http:www.datakind.org/
[Humanitarian Exchange Language]: http://hxlstandard.org/
