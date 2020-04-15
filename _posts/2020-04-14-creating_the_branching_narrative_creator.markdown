---
layout: post
title:      "Creating the Branching Narrative Creator"
date:       2020-04-15 01:12:07 +0000
permalink:  creating_the_branching_narrative_creator
---


When approaching my Project for the Rails section of my curriculum, I decided to challenge myself to implement as complex an association as I could conceive of: a model with a self-referential has_many relationship. What better way to demonstrate competence with Rails than to enable users to perform CRUD operations on such a hydra? Indeed, experience creating such an association could prove very handy in the future when designing a user model that has many other users as friends, for example. More importantly, such an application synergizes well with my interest in branching-narratives, wherein certain outcomes can have many precedents and antecedents. 

I'm not ashamed to admit that I accessed Stack Overflow extensively throughout this project, and its inception was certainly no exception. I settled upon using a join-table called "Branches" to connect parent "Documents" to child "Documents" within the same "Narrative". In the hopes of easing bugfixing and reducing overall development time I decided to try out writing my own spec tests, which I found quite helpful for ensuring my models behaved as I wanted them to. However, while writing tests for features of the application I discovered that I was actually testing the website in a rails (thin) server in practice so frequently that running and expanding upon these tests ended up seeming redundant. In forthcoming labs, I will try to pay closer attention to how feature tests are written, so that I can refine my approach to writing them so that they seem less redundant. 

Most of the CRUD-related aspects of the project were on the whole quite easy to implement. I was rarely mystefied as to any behavior for more than two or three executions of binding.pry. Most of the challenge was in deciding categorically on how the user should be able to access and mutate Documents- through what nested views, passing what objects to form_for helpers, deciding when to build objects for nested fields in forms, and so forth. Prior to this project I had a rather tenous grasp of controller filters, custom validators and view helpers, but now I regard them as indispensable. I feel quite ready to create my own projects using the knowledge I've been able to acquire thus far, and for that I am very grateful. Of course, it behooves me to wait until I am as competent designing and developing client-side content as I am designing and developing models and features. To this end, I must end this blog-post and proceed as quickly as possible to Module 14 of the curriculum.

Godspeed!
