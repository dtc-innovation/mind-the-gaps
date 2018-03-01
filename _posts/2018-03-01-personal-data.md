---
title: A survey with no personal data?
image: assets/posts/survey-question-neighbourhood.png
tags:
- findings
---

While conducting the first research phase of _Mind the Gaps_, we made **a concious decision to not ask for personal data** in the survey.

We made this decision for **privacy** and for **user experience** reasons.

The only form of identification we ask for is the _neighbourhood_ location. There is the administrative neighbouhood and the perceived neighbouhood. The people we talked to defaulted to the perceived neighbouhood.

{% include figure.html src="assets/posts/survey-question-neighbourhood.png" %}

# Why not asking for a postcode?

We could ask for the postcode in the UK. They look like `BS3 4ND`:

- `BS` represents the town
- `3` represents the ward
- `4ND` represents a smaller area, like a street or a block of houses

Although British postcodes are easy to validate, they could breach respondants privacy… when the postcode includes only one address for example.

In France, postcodes are an entirely different story.
They look like `33000`:

- `33` represents the county (_département_—an administrative layer in between cities and regions)
- `000` represents the city

Postcodes are broad and encompass a city or a city administrative district (Paris, Lyon and Marseille only). [IRIS codes][] ([LSOA][] equivalents) and [INSEE codes][] exist but nobody on the street knows about them.

French postcodes won't tell you _which part of the city we're talking about_ unless you have a postal address. But then, asking for a postal address can be precise enough in term of person identification.

So in the end **we ask only about the _neighbouhood_**. Which is easy to ask in a conversational form. It's like asking where you come from.


# Interpretation Bias

One reason there is no gender, no age and no ethnicity in our questions is because **we do not want to influence how responses can be understood**.

We don't want a response to be discarded because the respondant is "too old" or "too young". If the "age" does not matter as such, the bias is introduced by the _belief associated with "age"_.

We want responses to be treated equally thus we don't ask for these personal details. This ensures **analysis are not skewed with our own bias**.

Ultimately, personal details do not make a difference with how you perceive your neighbourhood.

# Trade-off

We know by doing such, we would not be able to address specific demographic issues (eg: women safety by night).
We would not be able to segment our data by demographics.

A way to work around the absence of personal data would be to join _Mind the Gaps_ data with neighbouhood demographic data.

# User experience matters

It is not a great user experience to have to self define ourselves, either in a conversation on the stret or on an online survey. Why would we have to say we are caucasian white? Why shall we state our gender?

Because the _Mind the Gaps_ project is more about **communicating signals**,
we embraced our principles by asking only neighbouhood informations.

# Subjectivity

Feelings are subjective. They are real. But they are tight to each person which express them. Hence the _subjectivity_.

Making the choice to not ask for personal data is also a way to avoid the complex intrication of subjectivity: shall we have to think differently about a subjective opinion because of these details?

We'd rather not. So **it's about removing another layer of subjective reading**.

# Conclusion

Individuals and their opinions are considered as equals at the survey/form level directly. Equality of analysis is built-in, by design.

[IRIS codes]: https://fr.wikipedia.org/wiki/%C3%8Elots_regroup%C3%A9s_pour_l%27information_statistique
[LSOA]: https://en.wikipedia.org/wiki/ONS_coding_system#Neighbourhood_Statistics_Geography
[INSEE codes]: https://en.wikipedia.org/wiki/INSEE_code
