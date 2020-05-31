---
date: "2020-05-30T10:30:00Z"
external_link: ""
image:
  caption: Illustration by Tristan Snowsill
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/TMSnowsill
# slides: example
summary: Methodological developments including the moment-generating function method.
tags:
- Health economic modelling
title: Advances in health economic modelling
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

I have a longstanding interest in methodological developments in health economic modelling. This project collects these and points to any relevant publications.

## Sojourn-dependent transitions

Markov models are extremely common in economic evaluation, but they have a structural limitation which means it is not possible to know the sojourn time in each state (time spent in that state) and use this to determine the rate of transitions to other states.

A typical workaround is to use tunnel states, but this is not without drawbacks.

I devised a method for calculating expected discounted outcomes when transitions between states are governed by sojourn-dependent time to event distributions. The method uses moment-generating functions and was presented at the Health Economists' Study Group in Bristol (Summer 2018) and [published in Medical Decision Making]({{< ref "/publication/snowsill-2019-a-new-method-for-model-based-health-economic-evaluation/index.md" >}}).

I have submitted a further development in this area to Medical Decision Making, which I presented at the South West Health Economists Meeting 2019.

## Probabilistic sensitivity analysis

Probabilistic sensitivity analysis is a way to understand how uncertainty in model parameters translates into uncertainty about what decision to make. It also underpins value of information analyses.

I have submitted an abstract to the [SMDM 42nd Annual North American meeting (October 2020)](https://smdm.org/meeting/42nd-annual-north-american-meeting) describing a new method for propagating uncertainty through a decision model and conducting probabilistic sensitivity analysis.