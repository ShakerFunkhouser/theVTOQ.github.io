---
layout: post
title:      "Ethics Codified"
date:       2019-09-12 16:34:34 +0000
permalink:  ethics_codified
---


The goal of my latest project, EthicsDB, is to give people a simple, modular way to express and circulate ethical arguments on various subjects. The views I created for the protoype are quite crude and could greatly benefit from some Javascript. Nevertheless, I think I comfortably satisfied the scope of the project by creating a comprehensive MVC application with working model-relationships, easy navigation, user accounts, and forms that facilitate CRUD operations for Users and the Ethical Arguments. Users may author, edit and subscribe to many ethical arguments. Accordingly, ethical aguments may have many authors, editors, and subscribers. At one point ActiveRecord presented a bug (via Sinatra) that suggested I would need polymorphism to redress. Quickly I discovered that wasn't the case, and merely needed to create new join tables or edit existing join tables. That fix seems so obvious now but unfortunately it didn't in the heat of the moment. 

As regards practicality, I frequently wonder if people will find this preliminary formulation of ethical arguments appealing, effective or persuasive. I guess I will only know after gathering feedback from users. Then again, how many people are really interested in ethics in first place? Likewise, I will only know after such a project is completed and deployed (with optimal SEO, of course- a term whose import I can only currently guess at).
