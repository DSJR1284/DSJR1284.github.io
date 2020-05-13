---
layout: post
title:      "Sorting The Difference "
date:       2020-05-13 02:23:44 +0000
permalink:  sorting_the_difference
---

In Ruby we come across a lot of data. One of the things we are consistently asked to do is iterate through the data we are given in different ways. 

In this blog post we are going to look at our **Sort** and **Sort_by** method in Ruby. 

**Sort** - Is a Ruby method that compares two elements by using the <=> (Spaceship Operator). 

Spaceship Operator <=>  - Takes two elements and compares them and give us differnt returns based on the 
comparison. 

0 if the values are equal (the order of the elements is unpredictable if the results are 0)

-1 a <=> b if a is less than b. 

1 a <=> b if a is greater than b 

Below is a simple code to show  the reuslts of sort when uses on an array of cars : 
```
cars =["Honda", "GMC", "Kia", "Ford", "Toyota", "Subaru"]

cars.sort { |a, b| a <=> b } #Passes two elsements into a block  and compares them with the <=> (Spaceship Operator). 

=> ["Ford", "GMC", "Honda", "Kia", "Subaru", "Toyota"] #Puts out our sorted array in alphabetical order. 
```

**Sort_by** - Is a Ruby method that takes in one elemment and you have to call a method the will be used to give you the return value for what your looking for. 

In the example below we are interating through our car_hash and  **"Sorting_by"** the keys of the hash. 

``` #
car_hash = {Kia: "Soul", Subaru: "Legacey", Honda: "Accord", Ford: "Focus", Toyota: "Camry", GMC: "Envoy"}

car_hash.sort_by { | k,  v| puts k}  #Telling our method to go through our hash and just pull out the Keys in the hash
  
=> Kia  #Puts just the keys of the hash. 
   Subaru
   Honda
   Ford
   Toyota
   GMC
```

***The difference between sort and sort_by is in the parameters to the block.***

This is just the begiing of what you can do with these two methods.There are many additional ways you can use Sort and Sort_by to help you iterate through data and make it your own. 

I hope this helps as a good introidcution to these two methods. 

Thank You for reading my blog and Happy Coding. 






