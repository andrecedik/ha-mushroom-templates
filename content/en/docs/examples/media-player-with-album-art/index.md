---
title: "Media player with album art"
description: "Media player that also shows an image of the currently played media"
lead: "Media player with album art"
date: 2022-10-13T11:06:06+02:00
lastmod: 2022-10-13T11:06:06+02:00
draft: false
images: []
layout: mushroom-template
menu:
  docs:
    parent: "examples"
    identifier: "mini-graph-f1b61262b280c0e04c493507567a06dc"
weight: 999
toc: true
credits:
  avatar_image: https://community.home-assistant.io/user_avatar/community.home-assistant.io/rhysb/45/310019_2.png
  name: Rhys
  username: rhysb
  type: ha-forum
  link: https://community.home-assistant.io/t/mushroom-cards-build-a-beautiful-dashboard-easily/388590/2570
---

## Compontents used

- {{<component-description name="mushroom-media-player-card">}}
- {{<component-description name="lovelace-card-mod">}}

## Image

![foo](media-player-with-album-art-light.png "bar")

## Code

{{<highlight yaml>}}
{{<read-file "media-player-with-album-art.yaml">}}
{{</highlight>}}


