---
title: "HVAC with chips"
description: "Climate controller with animated icons"
lead: ""
date: 2022-10-14T10:06:26+02:00
lastmod: 2022-10-14T10:06:26+02:00
draft: false
images: []
layout: mushroom-template
menu:
  docs:
    parent: "examples"
    identifier: "hvac-with-chips-5eb8af9e41349ad20320442800e034c3"
weight: 999
toc: true
credits:
  avatar_image: https://community.home-assistant.io/user_avatar/community.home-assistant.io/rhysb/45/310019_2.png
  name: Rhys
  username: rhysb
  type: ha-forum
  link: https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/2571
---

## Compontents used

- {{<component-description name="mushroom-climate-card">}}
- {{<component-description name="lovelace-card-mod">}}

## Image

![foo](hvac-with-chips-light.gif "bar")

## Code

{{<highlight yaml>}}
{{<read-file "hvac-with-chips.yaml">}}
{{</highlight>}}
