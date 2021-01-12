---
layout: post
title:      "CORS and my Javascript&Rails Project"
date:       2021-01-12 01:20:24 +0000
permalink:  cors_and_my_javascript_and_rails_project
---


In the project adventure, I learned about CORS, which stands for Cross-Origin Resource Sharing. This gem is actually in the gemfile already, you simply have to uncomment it out. Run bundle and add your middleware code in the config folder for CORS to properly be used. So let's talk about what it is and how CORS works. CORS is a mechanism that allows for restricted resources to be requested from a different origin. This type of mechanism helps keep the tranfer of data more secure. Some of the requests that could be used are GET, POST, DELETE, PATCH, and more. In this project, I used GET, POST and DELETE. It was very easy to use. 

I believe the project was very simple. Nothing out of the ordinary, but just like any other programming language, there are small details to easily miss. It can get a bit confusing between writing an id versus a class as a dataset. the syntax goes, if its an id, then put the pound sign in front of the id variable when gathering said elements. It is a bit easier to get confused with just the one page to workd with. At least with the previous projects, you are able to see the url on the top for the web page. On the plus side, you can use the handy-dandy inspect tools. Insise the inspect tools, you can debug by simply going to sources and just like using pry, pause your program and take it step by step. Doing so was extremely helpful.
