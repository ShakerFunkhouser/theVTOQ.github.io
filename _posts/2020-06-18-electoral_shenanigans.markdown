---
layout: post
title:      "Electoral Shenanigans"
date:       2020-06-19 03:07:47 +0000
permalink:  electoral_shenanigans
---


For my Javascript project, I decided to create a very simple proof of concept for a game I conceived of way back in 2015 at the earliest, when intrigue regarding the 2016 general election was nascent. One of the reasons I began this bootcamp was to create this project and many others like it, so it is very exciting to have assembled a fraction of the scope of my vision. 

Development went quite smoothly all things considered: for the most part, the bugs I encountered turned out to be rather simple semantic errors rather than gaping design flaws. Using rspec tests proved invaluable, and I cannot recommend them enough. Having a coherent backend made coding the frontend much easier than it would have otherwise. My greatest challenge happened to be after I met the technical requirements for the project and while attempting my first stretch goal: creating NPC's with reandomized trait values. Sounds easy enough, but I encountered this bug where character.trait_statuses yielded records having current_points equal to 0.0, but where character.trait_statuses.where("current_points > ?", 0) yielded all the records I expected to generate with nonzero values for :current_points. As of the time of writing this blog, I am still absolutely mystified, and have invested several hours trying to reconcile these seemingly separate realities. Hopefully I will have solved this conundrum by the time I record a demo and present my project, but, in the interests of practicality, I am only allotting an additional 24 hours to this pursuit. Wish me luck!

Anyways, I hope this blog finds you well in these strange times. Godspeed!

-Shaker Funkhouser
