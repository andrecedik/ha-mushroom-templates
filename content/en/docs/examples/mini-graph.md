---
title: "Mini Graph Card"
description: "A mini graph"
lead: "A mini graph"
date: 2022-10-04T22:44:46+02:00
lastmod: 2022-10-04T22:44:46+02:00
draft: false
images: []
menu:
  docs:
    parent: "examples"
    identifier: "mini-graph-f1b61262b280c0e04c493507567a06dc"
weight: 999
toc: true
---

## Compontents used

{{<component-description name="mini-graph-card">}}

## Image

foo

## Code

{{< highlight yaml >}}
type: custom:stack-in-card
cards:
  - type: horizontal-stack
    cards:
      - type: custom:mushroom-entity-card
        entity: sensor.livingroom_temperature
        name: Temperatur
        icon_color: red
      - type: custom:mushroom-entity-card
        entity: sensor.livingroom_humidity
        name: Luftfeuchtigkeit
  - type: custom:mini-graph-card
    entities:
      - entity: sensor.livingroom_temperature
        color: red
      - entity: sensor.livingroom_humidity
        y_axis: secondary
    group: true
    points_per_hour: 1
    show:
      icon: false
      legend: false
      name: false
      state: false
{{< / highlight >}}
