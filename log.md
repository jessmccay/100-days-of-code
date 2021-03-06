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

### Day 25: April 29, Saturday

**Today's Progress**: Attmepted a random quote generator.

**Thoughts** I have lost some steam. I will have to attempt this again because I know I can do it. I know math.random will be a big part of the generator.  

**Link(s) to work** 
 https://www.freecodecamp.com/challenges/build-a-random-quote-machine
 
 ### Day 26: April 30, Sunday

**Today's Progress**: Personal website

**Thoughts** Haven't been quite as productive as the previous 20 days or so. Enjoyed taking a look back at this personal site I made. It needs cleaned up but has some great fashion images featured on it.   

**Link(s) to work** 
https://github.com/jessmccay/personalSite

### Day 27: May 1, Monday

**Today's Progress**: Random Quote generator on codepen. Restarted this. I was able to append the quotes after the users clicks the new quote button.

**Thoughts** I might need to use Ajax for this. Right now I am just using jQuery. I am feeling fueled again today! I love programming!

**Link(s) to work** 
https://codepen.io/jessica406/full/YVVdYN/

### Day 28: May 2, Tuesday

**Today's Progress**: Finished random quote project excluding tweet functionality. Today I used jquery, javascript, css and html.

**Thoughts** Yesterday I was using .append for the quotes and that was just adding quote after quote. Now I have put .html instead which is updating the text! 

**Link(s) to work** 
http://codepen.io/jessica406/full/YVVdYN/

### Day 29: May 3, Wednesday

**Today's Progress**: Worked on Tweet quote functionality for quote generator on codepen.

**Thoughts** Progress was made, will continue on this tomorrow. I have almost got the tweet functionality I'm guessing it's something simple that I either havent done or have mispelled etc.

**Link(s) to work** 
http://codepen.io/jessica406/full/YVVdYN/

### Day 30: May 4, Thursday

**Today's Progress**: Worked on personal portfolio. New background, messing with border, image size, placement.

**Thoughts** I decided to work on a easier project as I had made the trip from San Diego to Tempe. Glad I still made the effort to do a little coding.

**Link(s) to work** 
I didnt push.. https://jessmccay.github.io
### Day 31: May 5, Friday

**Today's Progress**: Seeded database in my apartment app. Worked on stories for the app mostly to do with roles.

**Thoughts** 
Good review of seeding and also cancancan and rolify. Remember to .create instead of .new ! 

**Link(s) to work** 
https://github.com/jessmccay/apt_app

### Day 32: May 6, Saturday

**Today's Progress**: Completed my code generator project. Successfully integrated a 'tweet quote' function. Also, added an event click so that the background will change to a random color when the quotes are changed.

**Thoughts** 
Feeling very good today! I feel accomplished and happy to complete the stories required for my quote generator!

**Link(s) to work** 
http://codepen.io/jessica406/pen/YVVdYN

### Day 33: May 7, Sunday

**Today's Progress**: Started a weather app. Got an Api for the temp and also integrated html5 geolocation to get the latitude and longitude of the current user.

**Thoughts** 
Need to ready more documentation on the dark sky api

**Link(s) to work** 
https://github.com/jessmccay/weather_app

### Day 34: May 8, Monday

**Today's Progress**: Continued my weather app. Added toggle with css and worked on switching from farenheit to celsius and back.

**Thoughts** 
I thought I could just change the html with an on click event for the toggle I added but it wasnt working. Will try a new way tomorrow. I also tried switch cases but that wasnt quite right either.

**Link(s) to work**
https://github.com/jessmccay/weather_app/commit/5b5ad4d72f6d7adcd2b05f4e040761e641684413

### Day 35: May 9, Tuesday

**Today's Progress**: Worked on my personal portfolio.

**Thoughts** 
Need to practice a bit more with min and max for different screen sizes.

**Link(s) to work**
https://github.com/jessmccay/jessmccay.github.io
### Day 36: May 10, Wednesday

**Today's Progress**: Weather app

**Thoughts** 
In a coding little slump

**Link(s) to work**
https://www.freecodecamp.com/challenges/show-the-local-weather

### Day 37: May 11, Thursday

**Today's Progress**: Weather app trying out a sample api call

**Thoughts** 
Needs work. Not really getting how to integrate....

**Link(s) to work**
https://github.com/jessmccay/weather_app/commit/ea80a949eb86fade798f89eca94c0a26d22301e5

### Day 38: May 12, Friday

**Today's Progress**: Weather app redo, app is working.

**Thoughts** 
I'm feeling revamped. I am understanding api's and how to used them. Its just a matter of grabbing the right parts of the json object. I followed along with youtube coding 360 weather app tutorial.

**Link(s) to work**
https://github.com/jessmccay/weather_app

### Day 39: May 13, Saturday

**Today's Progress**: Seeded data for wedding app. finished testing the seeded data and also utilized DatabaseCleaner.

**Thoughts** 
Seeding data is so useful. DatabaseCleaner

**Link(s) to work**
https://github.com/jessmccay/wedding_app/commit/1b30ccb3f8dc48ff735cc2713879a654284e6ebc

### Day 40: May 14, Sunday

**Today's Progress**: Finished functionality for weather app. Switch farenheit to celsius on click.. turned all to buttons, change background depending on temp.

**Thoughts** 
Enjoyed making this. I followed a tutorial on youtube so I was able to rewind and rewatch. It helped my understanding of everything by going through step by step. Still needs a bit more styling! Cool App!

**Link(s) to work**
http://codepen.io/jessica406/full/OmOBoO/
https://github.com/jessmccay/weather_app/pull/3

### Day 41: May 15, Monday

**Today's Progress**: Started to work on accordian menu for categories on my wedding app.

**Thoughts** 
Not really working. I followed W3Schools example but it may have something to do with where I'm placing the erb.

**Link(s) to work**
https://github.com/jessmccay/wedding_app/tree/categories
### Day 42: May 16, Tuesday

**Today's Progress**: Added accordian menu for task categories. All categories are showing. Also a fixed table in database.
**Thoughts** 
I remembered making an accordian menu to be so much easier! I have made the basic menu but it doesnt open up to anything further. I ran into some issues with errors in the app but was able to track down the problem! Also, I noticed that our column in the categories table was named 'descripton' so I updated the database and changed it to 'description'.

**Link(s) to work**
https://github.com/jessmccay/wedding_app/tree/categories

### Day 43: May 17, Wednesday

**Today's Progress**: Still working on accordian.. 
**Thoughts** 
Pretty puzzeled as to why the accordian wont expand......nothing happens at all when clicked. 

**Link(s) to work**
https://github.com/jessmccay/wedding_app/tree/categories

### Day 44: May 18, Thursday

**Today's Progress**: added a new accordian, Figured out that seeded data had spelling error and that is why nothing was being rendered to categories.description.  
**Thoughts** 
Thank you rails c! It showed all categories.descriptions as being null so it led me to go check the seed files!
I know I could get the accordian to work just fine if I put the information in manually, but, I'm pretty sure I can just write a function to do the work for me! So I just need to figure out how to write it..

**Link(s) to work**
https://github.com/jessmccay/wedding_app/tree/categories

### Day 45: May 19, Friday

**Today's Progress**: adding logo to mps site. Updating site look. Figuring out what is targeting what in our html5 template.
**Thoughts** 
A LOT going on in the HTML5 template. Hard to figure out what is doing what. Have figured out a few things and am changing color themes. #frustrating

**Link(s) to work**
https://github.com/mpsdevs/mpsdevs.github.io


### Day 46: May 20, Saturday

**Today's Progress**:MPS SITE colors. Again finding what is targeting what in our HTML5 Theme  
**Thoughts** 
Still quite frustrated with this theme. Not making a whole lot of progress for the amount of time spent on this. Regardless, I have successfully added our logo as the site  background and it looks great!

**Link(s) to work**
https://github.com/mpsdevs/mpsdevs.github.io

### Day 47: May 25, Thursday

**Today's Progress**:Facelift for my weather app! Changed a few of the conditionals so they are dependent upon the type of weather rather than the degrees. I have also done away with the buttons and changed how the information is displayed to the user. Attempted to host of github pages.
**Thoughts** 
I have been on a little hiatis! FAMILY life, tiredness and traveling! FEELS GREAT to be back on the roll. Very pleased with how my weather app is turning out. Having trouble with github pages. My app works wonderfully on my local machine, but it is showing blank on github. 

**Link(s) to work**
https://github.com/jessmccay/weather_app
https://jessmccay.github.io/weather_app/

### Day 48: May 26, Friday

**Today's Progress**:I have made a new website for MPS Devs. Also, the accordian for task categories is DONE on the wedding app.

**Thoughts** 
So much fun pair programming from Montana with my colleague all the way in India! So glad to have figured out the accordian menu with our seeded data! I had a hunch that the 'data-parent' was the panel above and that turned out to be true so we used a variable to increment for each new panel!

**Link(s) to work**
https://github.com/jessmccay/wedding_app

### Day 49: May 27, Saturday

**Today's Progress**:Working on the NEW MPS website. Added more seed data for tasks on the wedding app.

**Thoughts** 
Site is looking good. My background image wasnt working and I figured out in had the wrong path. 

**Link(s) to work**
https://github.com/jessmccay/wedding_app

### Day 50: May 29, Monday

**Today's Progress**: Taking a new lesson on functional programming. Finished lesson 1 and quiz 1 with a score of 100%.

**Thoughts** 
Nice review. Did very well on the quiz. I want to make sure I am staying sharp (and improving) when it comes to functional programming. Front end development is shifting towards it!  

**Link(s) to work**
https://preethikasireddy.typeform.com/to/z4dqG8
### Day 51: May 30, Tuesday

**Today's Progress**: A bit of functional programming review and writing tests for wedding app.

**Thoughts** 
Story officially closed for wedding app! All previous test still passing. Progress. 

**Link(s) to work**
https://preethikasireddy.typeform.com/to/xjXSci
https://github.com/jessmccay/wedding_app/commits/master

### Day 52: May 31, Wednesday

**Today's Progress**: Applying a new API key from openweathermap for my weather application. Trying to fix json call.

**Thoughts** 
Trying to figure out whats wrong with my weather app. It is still working on my local machine but it no longer works on codepen. I am watching some youtube tutorials and trying to switch a few things such as the JSON address and API key. 

**Link(s) to work**
https://codepen.io/jessica406/pen/OmOBoO

### Day 53: June 4, Sunday

**Today's Progress**: Figured out problem with codepen weather app has to do with http! 

**Thoughts** 
codepen is strictly secure now. (https). I am attempting to rewire this project. I am going to need a new api.

**Link(s) to work**
https://codepen.io/jessica406/pen/OmOBoO

### Day 54: June 5, Monday

**Today's Progress**: Weather app. Restarted project. Found a W3Schools live example for geolocation. Totally started over on my weather app.

**Thoughts** 
The geolocation I was previously using was oddly off. Trying to find a more accurate one and how to use it.

**Link(s) to work**
1. https://codepen.io/jessica406/pen/XgJQQE
2. https://codepen.io/jessica406/pen/OmOBoO

### Day 55: June 6, Tuesday

**Today's Progress**: New start (again) on my weather app.

**Thoughts** 
Okay so once again I started over. I have been following a tutorial on youtube, using jquery getJSON... unfortunely I just ran into the issue of not being able to use https for ipinfo.io. You have to be a paid user! Will continue this journey.. I'm determined. On the upside, the weather app on my local machine is improving .:)

**Link(s) to work**
 https://codepen.io/jessica406/pen/OmOBoO
 
 ### Day 56: June 7, Wednesday

**Today's Progress**: Continuing on my weather app. Following a tutorial.

**Thoughts** 
I thought I was on to something! Again...You have to have a PAID account to get the secure https geolocation api. ughhhh.
**Link(s) to work**
httpscodepen.io/jessica406/pen/OmOBoO

 ### Day 57: June 9, Friday

**Today's Progress**: Tried accessing weather app through Microsoft edge rather than chrome to see if it would work. 

**Thoughts** 
It most definitly is a conflict of the geolocation http and weather https! You cannot do that in Chrome. I read up on  this freecodecamp project and it turns out I am DEFINITLY NOT the only one with this problem. Just like me, others had their app working temporarly on codepen only to find it stop working shortly after. It is just a conflict! I do see light at the end of the tunnel, though, apparently Accuweather is secure and FREE!

**Link(s) to work**
https://codepen.io/jessica406/pen/QgyPKJ?editors=1111
