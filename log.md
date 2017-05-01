# 100 Days Of Code - Log

### Day 1: April 5, Wednesday

**Today's Progress**: I've completed 10 hours worth of work in CSS and Bootstrap!

**Thoughts** I feel good about this start to my 100 days of Code challenge. I learned a few extra things that I did not previously know about! 

**Link(s) to work**
1. [Check out my cat app] https://github.com/jessmccay/100DaysCode/blob/master/catapp.html

### Day 2: April 6, Thursday

**Today's Progress**: Today I mob programmed on a Ruby on Rails application. We worked on customizing the devise sign up fields!. We struggled for a little while as the custom fields were not showing up. We worked through it and by the end of our work session we amade it happen! 4 hours spent on this today!

**Thoughts** I am so excited to be back working with rails, especially on this project in paticular. Mob programming was fantastic. Working with two other minds made our work flow so much more powerful. Also, we our thinking about doing a documentation on this to help our fellow developers!

**Link(s) to work**
1. [Check out our code]https://github.com/jessmccay/wedding_app/commit/390b5fa040ecd2dcb512c212cb7b29d372a8d9db

### Day 3: April 7, Friday

**Today's Progress**: Today was about TESTING! Again, I mob programmed with my team on our personal app. We tested the code that we wrote yesterday for the additional fields for the devise form. Also we added the same fields to our edit form. Additionally, we were able to add a task feature and of course test it. 

**Thoughts** Testing is very important to ensure good code. I am pleased that we are not counting any story as finished until tested and passing. Note: when testing devise field for email make sure to include the @, otherwise, the test fails and the user does not get saved into the database.

**Link(s) to work**
1. [Check out our code]https://github.com/jessmccay/wedding_app/commit/5c5c5ef5ecc6cbe0ce5c30a1be8d9a8572258c3f

### Day 4: April 8, Saturday

**Today's Progress**: I refreshed myself on some basic javascript. Something I learned was that if you are inside a function and declare a variable without 'var', it automatically becomes part of the global scope, which can cause problems! 

**Thoughts** I felt pretty strong on most I went over today. I am glad I did it becasue there were a couple of new things I was intoduced to and on top of that I just feel that much more confident.

**Link(s) to work**
1. [Check out my cat app] https://www.freecodecamp.com/challenges/stand-in-line

### Day 5: April 9, Sunday

**Today's Progress**: Continuing practicing javascript. Todays focus was on comparison operators , if / if else statements. I worked for a little over an hour.

**Thoughts** Overall this was review, Although there is something quite important that I learned today. I previously wasnt really sure what the difference was or if there even was a difference between == and === . Now I know that YES, there is a difference. For example if I was to compare 5 == "5" , this would return true. Now if I compared the same  5 === "5" this would return false. The == converts one of the two data types so that they are the same while the 'strict' === does not convert.

**Link(s) to work**
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js
https://www.freecodecamp.com/challenges/selecting-from-many-options-with-switch-statements

### Day 6: April 10, Monday

**Today's Progress**: Mob programmed Ruby on Rails App. This included making buttons, creating categories for tasks, creating seed data and feature testing. Later today I will be practicing more javascript.

**Thoughts** I feel great. I am more than excited to be making progress on this rails app. We learned about to seed data! Very exciting and useful! 

**Link(s) to work**
https://github.com/jessmccay/wedding_app/commit/7ae607674aa483fef6f744aed2b314b2ab4dbb79
https://github.com/jessmccay/wedding_app/tree/categories


### Day 7: April 11, Tuesday

**Today's Progress**: Continued on Javascript. Learned and coded javascript switch cases, integrated them into code with if statements. Also did a bit of work with javascript objects.

**Thoughts** I have never used switch cases before, let alone know they existed. They seem pretty useful. I LOVE if statements and switch cases seem to go along with that. Switch cases are a bit less code if you have a lot of different options, making the code cleaner and a bit more clear. Glad I know about them now!

**Link(s) to work**
https://github.com/jessmccay/100DaysCode/commit/acb780be93a408897c35f7aff7b52239f8a67fca


### Day 8: April 12, Wednesday

**Today's Progress**: Today I made an app and integrated Devise! I did TDD development (test first). I worked for about 4 hours today on this. 

**Thoughts** It was great pracitice not only with Devise and getting to know how to use it better but also with writing tests. Model tests in particular. 

**Link(s) to work**
https://github.com/jessmccay/apt_app

### Day 9: April 13, Thursday

**Today's Progress**: I used rolify and cancancan for the first time today. I added them to the apartment app that I made yesterday. I wrote a couple of new tests and had to rewrite a few old tests to fit the new roles.

**Thoughts** I feel like I have a good grasp on rolify and cancancan although, I do not have the best grip on writing tests for the roles. 

**Link(s) to work**
https://github.com/jessmccay/apt_app
https://github.com/jessmccay/apt_app/tree/cancancan_testing


### Day 10: April 14, Friday

**Today's Progress**: Working on feature tests. After integrating cancancan and rolify I had to reconfigure most of the tests. I have most of them passing. I was trying to test user roles: ability.should_not be_able_to(:destroy, Apartment.new). Haven't been able to get this to pass yet.

**Thoughts** I struggled a bit tonight. I did a 6 hour drive before programming so that could be affecting me! I will try this again tomorrow.

**Link(s) to work**
https://github.com/jessmccay/apt_app/tree/cancancan_testing

### Day 11: April 15, Saturday

**Today's Progress**: Continued Javascript practice. Working with objects and their properties. praciticed adding properties as well as changing the value of a property and also deleting. I did a lookup table which is something I was not familier with. 

**Thoughts** Overall good. I enjoy learning new things. I left off on " hasOwnProperty() " I can think of a couple expamples in my past when this would have been very useful!

**Link(s) to work**
https://github.com/jessmccay/100DaysCode/commit/8ac2ec037209a9d71d482e2f07d7670b0d7a3438
https://www.freecodecamp.com/challenges/testing-objects-for-properties#?solution=%0A%2F%2F%20Setup%0Avar%20myObj%20%3D%20%7B%0A%20%20gift%3A%20%22pony%22%2C%0A%20%20pet%3A%20%22kitten%22%2C%0A%20%20bed%3A%20%22sleigh%22%0A%7D%3B%0A%0Afunction%20checkObj(checkProp)%20%7B%0A%20%20if(myObj.hasOwnProperty(checkProp)%20%3D%3D%3D%20true)%20%20%0A%20%20%20%20%20return%20checkProp%3B%0A%20%20%0A%20%20else%20%0A%20%20%20return%20%22Not%20Found%22%3B%0A%20%20%0A%7D%0A%0A%2F%2F%20Test%20your%20code%20by%20modifying%20these%20values%0AcheckObj(%22gift%22)%3B

### Day 12: April 16, Sunday

**Today's Progress**: Slow and Steady with the Javascript practice. Got through the hasOwnProperty method. Worked on nested arrays in objects and how to access them using dot and bracket notation. Also got into for loops.

**Thoughts** I'm pretty comfortable with for loops (and love them). I stuggled with the hasOwnProperty function I was writing for a while. It seemed everything looked right to me! I finally googled it and found out that when returning | myObject.checkProp |(is looking for a property literally called checkProp) ACTUALLY needed to be return | myObject[checkprop]. You have to use the bracket notation which is looking at the variable passed to the function and using its content as the lookup value

**Link(s) to work**
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js

https://www.freecodecamp.com/challenges/iterate-through-an-array-with-a-for-loop#?solution=%0A%2F%2F%20Example%0Avar%20ourArr%20%3D%20%5B%209%2C%2010%2C%2011%2C%2012%5D%3B%0Avar%20ourTotal%20%3D%200%3B%0A%0Afor%20(var%20i%20%3D%200%3B%20i%20%3C%20ourArr.length%3B%20i%2B%2B)%20%7B%0A%20%20ourTotal%20%2B%3D%20ourArr%5Bi%5D%3B%0A%7D%0A%0A%2F%2F%20Setup%0Avar%20myArr%20%3D%20%5B%202%2C%203%2C%204%2C%205%2C%206%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20below%20this%20line%0Avar%20total%20%3D%200%3B%0Afor(var%20i%20%3D%200%3B%20i%20%3C%20myArr.length%3B%20i%20%2B%2B)%20%7B%0A%20%20total%20%2B%3D%20myArr%5Bi%5D%3B%0A%7D%0A%0A

### Day 13: April 17, Monday

**Today's Progress**: Javascript nested loops.

**Thoughts** I struggled on one problem almost the entire hour. I think it was just one of those times that I was tired and needed to take a break from it and come back later.

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode


### Day 14: April 18, Tuesday

**Today's Progress**: Practiced Javascript nested loops, generating random fractions and whole numbers.

**Thoughts** Was able to get through the problem from yesterday. Used a for loop. Just got into the Math.random practice which I am familiar with but the way I learned to do the inclusive min, max range was a little different than I had learned before.

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js

### Day 15: April 19, Wednesday

**Today's Progress**: FINISHED intro Javascript! (WOO!) Practiced: Regular expressions.  Also did Object Oriented Programming: contructors, initialization,  public methods and private methods for objects. Reduce, filter, map, concat, join, split for arrays

**Thoughts** I have learned a lot of this in Ruby. It's so similar so that made me feel excited that I really could pick it up quite easily and actually it solidified my understanding of things (initializing, etc). I have used the .map method before but didnt totally understand it as it was the first time I was exposed to it. Now that I have gone over it again it seems so easy! Was also exposed to a couple of new things: Regular Expressions, .reduce method (to condense arrays). You can also concat arrays using the .concat method!

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js
### Day 16: April 20, Thursday

**Today's Progress**: Algorithms Day 1. 

**Thoughts**  WEll, this is what I've been waiting for. I want to be the best programmer I can be so that means being go at algorithms. I stuggled to figure out the answer of the factorial, as I didnt know if i should be using some type of loop or how I was going to accomplish the task.

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js

### Day 17: April 21, Friday

**Today's Progress**: Algorithm practice for 2-3 hours

**Thoughts**  A bit of trial and error. The practice I had during my internship at ThoughtSTEM really helped me with writing algorithms. I enjoy the challange again and working through it.

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js

### Day 18: April 22, Saturday

**Today's Progress**: I mentored 3 HighSchool girls and 1 college girl for 8 hours today at a womans hackethon! I also learned about how image facial recogition works. Tonight I continued on my algorithm practice for 1 hour. 

**Thoughts** Embedded for loops came in very handy today. Again, I am so please that I got so much practice at ThoughtSTEM working on algorithms. It is like it conditioned my brain for this "different" way of thinking! WONDERFUL day!
**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/commit/d4e3f72f743dac9ab6516cbc536328ebe512d369

### Day 19: April 23, Sunday

**Today's Progress**: Wrote an algorithm function to truncate a string. 

**Thoughts** This took me a bit over an hour. I knew I was quite close, but very important to return in the right place and account for each type of case. Great feeling to get the function to work. Very much enjoy writing algorithms.
**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js

### Day 20: April 24, Monday

**Today's Progress**: I did just an hour today, still practicing algorithms.

**Thoughts**  I am getting better at commenting on my code. 
**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js

### Day 21: April 25, Tuesday

**Today's Progress**: I spent almost 2 hours on an algotithm tonight. I am trying to get rid of all the falsy values from an array. I have not solved this yet. 

**Thoughts** So I only am stopping because It is getting pretty late. I was working on this a little yesterday and when I came back today, I had a different outlook on it as in a new strategy that came to me. false == 0 right? and true == 1? well I thought that maybe I could compare the elements in the array with 0 or 1 but that didnt work... I tried a few other ways as well. Tomorrow I will look more into using the filter() function because It seems thats how it "wants" to be solved. Although, I'd rather find 'my own' way to solve it, so we will see.
**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/commit/e7f4518d35a388bf97f611a3b127080f427e71b9
https://github.com/jessmccay/100DaysCode/blob/master/javascript.js

### Day 22: April 26, Wednesday

**Today's Progress**: Completed filter function. I also completed writing a method that takes a number and adds it to a existing array and then sorts that array and returns the index of where the number ended up in the array.

**Thoughts** sSmetimes it is best just to think simply! The simplest of code is what usually can help tests pass rather than some extra complicated code.

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/commit/a31604803d2606ceddf744f1efda38d3f84e4c7a

### Day 23: April 27, Thursday

**Today's Progress**: Started JSON and Ajax, Triggering click events with jQuery.

**Thoughts** Mostly a refresher, although I couldn't quite remember how to do the json call.. So good to go over it again.

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/commit/875846227d2fd647403b3b306445c7449a6505bb

### Day 24: April 28, Friday

**Today's Progress**: Finished my Ajax review!

**Thoughts** I will need more practice on Ajax but this lesson went quickly and was suprisingly easy. I was introduced a few months ago to this and its great to be exposed to it once again.  

**Link(s) to work** 
https://github.com/jessmccay/100DaysCode/blob/master/AjaxJSON.js

### Day 24: April 29, Saturday

**Today's Progress**: Attmepted a random quote generator.

**Thoughts** I have lost some steam. I will have to attempt this again because I know I can do it. I know math.random will be a big part of the generator.  

**Link(s) to work** 
 https://www.freecodecamp.com/challenges/build-a-random-quote-machine
 
 ### Day 24: April 30, Sunday

**Today's Progress**: Personal website

**Thoughts** Haven't been quite as productive as the previous 20 days or so. Enjoyed taking a look back at this personal site I made. It needs cleaned up but has some great fashion images featured on it.   

**Link(s) to work** 
https://github.com/jessmccay/personalSite
