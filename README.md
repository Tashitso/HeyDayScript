# HEY DAY
---------
 Hey Day is an AU tradition which unites the Auburn Family and promotes a friendly atmosphere known as HEY DAY! This event is organized by Auburn Univeristy's student body and members of the Student Government Association. Learn more about the history of HEY DAY and also get more details about this year's HEY DAY [Click here](http://sga.auburn.edu/hey-day/)
 
 # HEY DAY Shell script 
 ----------------------
 ```Shell
#!/bin/sh
   #ask the user to enter their name 
   echo "Enter your name"
   
   #reads the entered name and assigns it to a variable name 
   read name 
   
   #print Hey the name! 
   echo "Hey $name!"
```
# HEY DAY Perl script
--------------------
```perl
#!/usr/bin/perl -w
use feature 'say';

   # ask the user to enter their name
   say "Enter your name\n";

   # <> operator takes input and variable name equals input value
   $name = <STDIN>;
   
   # <>returns a newline character, use chomp function to remove it
   chomp($name);
   
   # print Hey and then the value of name variable
   say "Hey $name!\n";
```
 
   
   
   
   
