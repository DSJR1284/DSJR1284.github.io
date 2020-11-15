---
layout: post
title:      "Mapping and TDD  MVC "
date:       2020-11-11 14:33:15 -0500
permalink:  mapping_mvc
---


When I started this project. It was a bit overwhelming. I felt like there was alot of information to process extremly quickly.

One of the tips I have heard through my short coding journey is to take a big problem and to break it into smaller section. 

So before tackling this project I decided to  make a map of how I wanted my MVC to behave and what attributes I wantekd my Users and my Comics to have. 

I wanted my Users to have a : 

-Username
-Password
-Image 
-Bio 

I wanted my Comics to have:

-Title
-Image
-Blurb

The relationship bewtween the two was also mapped out with a User having many comics and comics beloing to a user. 

So before I wrote any code there was already an idea of how this application should work.  

This also help becasue when It came to making my views, there was already and idea of what to display to the user.


Mapping out the routes in the controller was easily the biggest challegne.  It was a lot of trial and error or as we like to say TDD (Test Driven Development). 

Using the Corneal gem helped out a lot due to having some built in html. I was able to test my routes to make sure I ended up extacly where I wanted to go before writing any code in my views. 

Building out your controllers will take time. The best advie is test and test often. Take advantage of `binding.pry` when ever you can to see excatly what your are getting and if your code is working the way you want it to.  

Having a good map is important and it helps you see exctaly how you want your app to work. It also allows you to make changes without have to rework a lot of code.

Testing you code often allows you to see exactly what you are getting and if your code is working the way you want it to without moving to far ahead. 


Be patient with yourself and the process.

Happy Coding :-). 




		 
			 
		 
	



 
