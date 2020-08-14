---
layout: post
title: "Day 5 Blog"
author: Thenuka Peiris
---

# Day 5 Summary
Today, we basically used Numpy, which is a widely used library in Python for scientific computing. Wile studying numpy arrays, we discovered that the arrays allowed for more convenient processes as opposed to how code would be written with normal lists. Using features like broadcasting, we are allowed to more easily manipulate our data. Upon learning more about numpy, we used that information to rewrite the code we had for calculating the pi value. After rewriting, we compared the run times between the original code and the rewritten code. There was a staggering difference in time when larger numbers of samples were introduced. Realizing the efficiency of the numpy arrays, we used what we learned to also rewrite the calculate_distance function we had. 

# Day 5 HW Discussion with team
Upon discussion, we concluded that the functions that would benefit the most would be calculate_total_energy, init_config, and calculate_pair_energy. These functions have nested lists that are integral to the function and could be simplified using numpy arrays.

# Day 5 HW Discussion with whole group
We were able to confirm that calculate_total_energy and calculate_pair_energy could be simplified with numpy arrays but since calculate_pair_energy is called twice in the simulation, it would be the most economically beneficial to rewrite that specific function and would save a great deal of time with much larger data sets.