---
layout: post
title: "Discussion about Cutoffs and Periodic Boundaries"
author: Thenuka Peiris
---

## Day 2 summary

Today, we basically used python to simulate functions and the data possessed within them. We started with a basic calculation of pi and then transitioned into calculating Lennard Jones energy functions.

## Cutoffs And Periodic Boundaries

When performing molecular simulations, there can occasionally be extremely large data sets for particles. Great ways of mitigating the inconvenience that arises huge data sets are by using cutoffs and using periodic boundaries. 

The benefits of cutoffs include simplification and cutting down on time but risks would probably include all aspects that are negatively affected by lesser accuracy. 

1. The maximum distance for any particle in each dimension would be have to be (box length)/2 in order to take into consideration the distance measured from 2 different directions.
2. The actual distance of the example ((0, 0, 0), (0, 0, 8)) would be 2(sigma) when accounting for the distance in the opposite direction. 

