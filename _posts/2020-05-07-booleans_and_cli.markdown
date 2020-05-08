---
layout: post
title:      "Booleans and CLI."
date:       2020-05-08 02:49:00 +0000
permalink:  booleans_and_cli
---

 
>   As I started to approcah my my first project as a newbie coder 
> I never thought that booleans would be a factor in and CLI application 
> *****Drum Roll*****
>
Once I got to actually wokring on the CLI class. Booleans were in full effect. 
espically when it came to checking user input with computer logic. 
>
```  def f get_covid_country
         input = gets.strip.downcase
         return input if input =="exit"
      ***   if !valid?(input)***
          puts "No Cases To Report"
         return "invalid"
         end 
        return input.to_i 
end 
		

The above code that has been highligthed uses the ! (Bang) Which is a Boolean Operator.  It was uses to convey user input from the user and respond. 

So not only were my eyes open to the importance of the Booleans Operators but I was also able to solve an issue with my code by using them. 

Thank you for reading my post untill next time Happy Coding. 
