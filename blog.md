Electricity disaggregation algorithms take as their input a
time-series which records the whole home's electrical power demand
(measured by, for example, a smart electricity meter). Disaggregation
algorithms aim to tease apart the energy consumption of different
electrical appliances.  One use is to provide domestic electricity
users with an itemised energy bill.  For example, here's the itemised
electricity consumption for my home:

![Disaggregated electricity consumption](http://jackkelly.github.io/EFL_talk/images/top_5_energy.png)

One ultimate aim of disaggregation is to help people to save energy.
There are *many* other uses of disaggregation.  But I am most
interested in its ability to reduce energy demand.

I started working on the computer science of energy disaggregation
five years ago: first as my MSc project and then as a PhD. Before I
started working on disaggregation, I found several papers which
suggested that disaggregation may help the general population to save
a significant amount of energy (maybe 10% or more).  This sounded very
exciting to me because I am, frankly, terrified about climate change
and I really want to help to engineer solutions to mitigate climate
change.  A 10% reduction in the UK's domestic electricity consumption
would equate to a CO2 emission reduction of about five million tonnes
of CO2 per year.  Not bad for a bit of code running on a handful of
servers!

As my PhD progressed, I buried my head in the computer science and
didn't pay much attention to the social science of energy
disaggregation.

Then, towards the end of last year (2015), I was having a pint with a
colleague whose opinions I greatly respect.  Towards the end of the
evening, he let slip that he believes that "energy disaggregation is
dead!"  By which he meant that it does not help the general population
to save energy.  This statement shocked me to the core and so, as soon
as I returned to my computer, I set about trying to prove my friend
wrong!

This mission to prove him wrong grew into an exhaustive, systematic
review of the literature on the effectiveness of disaggregated energy
feedback on energy reduction.  It is this review which I presented at
the Energy Futures Labs seminar on Tuesday and is also published this
week in a workshop paper called
"[Does disaggregated electricity
feedback reduce domestic electricity consumption? A systematic review
of the literature](http://arxiv.org/abs/1605.00962)" that will be presented at the
[3rd International NILM Workshop](http://nilmworkshop.org/2016/index.html)
in Vancouver on the 14th and 15th May 2016.

The [slides](http://jackkelly.github.io/EFL_talk) for my Energy
Futures Lab talk are available online.

I examined twelve studies on the efficacy of disaggregated energy
feedback. The average electricity reduction across these studies is
4.5%. However, 4.5% may be a positively-biased estimate of the savings
achievable across the entire population because all twelve studies are
likely to be prone to opt-in bias hence none test the effect of
disaggregated feedback on the general population.

Disaggregation may not be required to achieve these savings: Aggregate
feedback alone drives 3% reductions; and the four studies which directly
compared aggregate feedback against disaggregated feedback found that
aggregate feedback is at least as effective as disaggregated feedback,
possibly because web apps are viewed less often than in-home-displays
(in the short-term, at least) and because some users do not trust
fine-grained disaggregation (although this may be an issue with the
specific user interface studied).

Disaggregated electricity feedback may help a motivated sub-group of
the population ('energy enthusiasts') to save more energy
but fine-grained disaggregation may not be necessary to achieve these
energy savings.

Disaggregation has many uses beyond those discussed in my talk and my
paper but, on the specific question of promoting energy reduction in
the general population, there is no robust evidence that current forms
of disaggregated energy feedback are more effective than aggregate
energy feedback.

The effectiveness of disaggregated feedback may increase if the
general population become more energy-conscious (e.g. if energy prices
rise or concern about climate change deepens); or if users' trust in
fine-grained disaggregation improves; or if innovative new approaches
or alternative disaggregation strategies (e.g. disaggregating by
behaviour rather than by appliance) out-perform existing feedback. I
also discuss opportunities for new research into the effectiveness of
disaggregated feedback.
