---
layout: term
tags: [ process, shortest-path ]
title: stop state updating
short-description: Updating stop states when a stop is removed from the label stop queue.
notation:
example: .
type: process
alias: .
formats: [  ]
---
When stop i is removed from the label stop queue:
(1) Update stop states for all the adjacent nodes from stop i  via emanating non-motorized links and add them to the label stop queue.
(2) Update stop states for all the reachable nodes from stop i via feasible emanating transit links and add them to the label stop queue.
