---
layout: term
tags: [ model construct, pathfinding ]
title: pathfinding cost
short-description: The cost of each path as calculated during pathfinding, typically including costs of each leg plus some non-additive costs.  Because of the non-additive components (e.g. fares) and the adjustment of some components (e.g. travelers may leave their origin later than their preferred time to match their bus departure time), it’s typically computed fully only after the path is fully defined (origin to destination and all legs in between).  Differs from the simulation cost in that the travel times may not be accurate because the simulation step hasn’t happened yet which would load passengers onto vehicles, thereby slowing them down for boarding/alighting and possibly bumping passengers.
notation:
example: .
type: model construct
alias: .
formats: [  ]
---
