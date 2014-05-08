jQuery-in-30-days
=================

lesson 02 : Not so fast, jQuery  
In lesson two of this series, we'll review jQuery's ready method, and how it can be used to detect when the DOM is ready to be manipulated.  

Day 3: The Basics of Querying the DOM  
At this point, we know that we can search, or query the DOM using the CSS selectors that we’re already familiar with; but what about moving around the DOM after the fact? We’ll review a handful of traversal methods that you’ll use often in your projects, including children(), find(), parent(), closest(), and next().  

Day 4: Events 101  
Now, we get to move on to the fun part! In order to properly listen for when specific actions occur, such as the user clicking an anchor tag, or hovering over a particular section, we use event listeners. In this lesson, for demonstration purposes, we'll build a simple stylesheet switcher.  

Day 5: Events 201  
When binding event handlers to potentially hundreds of elements, event delegation can be your best friend. In this lesson, we'll build the obligatory accordion, while reviewing a handful of techniques, including nth-child, and passing a selector string to the on method.  

Day 7: Bind... Live... Delegate... Huh?  
Assuming that you're fully invested in learning jQuery, I won't be presumptuous enough to assume that you're exclusively learning from me (I wouldn't recommend it either). It's likely that, at some point, you've come across tutorials that reference the bind, live, and delegate methods. What are these, and why am I recommending that you don't use them? Find out in today's lesson.  

Day 8: Creating and Appending Content  
In today's lesson, we'll review jQuery's various methods that allow us to add content to the DOM. We'll make use of append, prepend, insertAfter, insertBefore, after, and before. Near the conclusion of the video, we'll build a simple utility script that dynamically creates callouts in a blog posting.  

Day 9: Slides and Structure  
You should have a fairly solid understanding of the basics at this point. Today, we're going to kick things up a notch. We'll learn how to use jQuery's slideToggle and fadeToggle methods to adjust the display of an element. In the process, we'll also focus on the structure of our code. Massively indented code and nested callbacks can be considerably difficult to maintain. We'll fix that!  

Day 10: The this Keyword  
Particularly when first being introduced to JavaScript, deciphering what the this keyword refers to in various contexts can be incredibly difficult. Hopefully, this lesson will make it much more understandable.  

Day 11: Modifying Effect Speeds  
We know that we can use milliseconds to specify how long a particular effect, such as slideDown, should last. However, jQuery provides a few named options as well, such as "slow" and "fast." Even better, because these settings are stored within a simple object, we can modify or extend it how we wish.  

Day 12: Creating Custom Effect Methods  
Sometimes, we may need more control than methods like slideDown or fadeOut are able to offer. In these situations, it's a cinch to extend jQuery's prototype to create reusable, custom methods.  

Day 13: Full Control With animate  
Up until this lesson, we've been using jQuery's helper methods, such as fadeIn and slideDown(). However, behind the scenes, these all reference the animate() method. Today, we'll review how to use it, and why it's necessary when you require full control over your animations.  

Day 14: Homework Solutions  
In the previous lesson, I assigned you some homework. Your instructions were to create a custom fadeSlideToggle() method, which combines the basic functionalities of both fadeToggle() and slideToggle() without referencing either of those methods directly. In this lesson, we'll work together, and finish the homework from scratch.  

Day 15: The Obligatory Slider  
It's time to make another jump; I'll need thirty minutes of your day for this lesson. We'll build the obligatory image slider. Though the code outlined is the most complex so far in this course, we'll review every detail.  

Day 16: Prototypal Inheritance and Refactoring the Slider  
In the previous lesson, we took our first stab at creating a functioning slider. There certainly wasn't anything wrong with that approach, but, today, we'll try again, and pay special attention to more sophisticated math/calculation techniques, as well as prototypal inheritance. Gasp! Don't worry; make it through this lesson, and you'll be well on your way to digging deeper into the JavaScript language.  

Day 19: $.each and Templating  
While not as glamorous and fun as working with effects, many of jQuery core's utility methods will be of tremendous help to you. In today's lesson, we'll review $.each, and a basic form of templating, which will allow us to keep from embedding lots of nasty HTML into our JavaScript.  

Day 20: Say Hello to Handlebars  
Today, we'll focus less on jQuery, and more on a third-party templating solution, called Handlebars (an extension of Mustache). It's important to remember that jQuery isn't some magical black box that is capable of everything. It handles a few things extremely well, such as working with the DOM, and performing AJAX requests. However, for other needs, such as code organization or templating, it's better to refer to third party tools.  
When it comes to templating, Handlebars is easily one of the most popular options. I'll show you how to use it in your projects.  

Day 21: The Twitter API  
In today's lesson, we'll review a handful of fun techniques, as we pull in tweets from the Twitter API. These techniques include templating, jQuery.map, AJAX, and code organization.  
It's vital that you understand the concepts in this lesson, so, if necessary, watch it twice for good measure!  

Day 22: Filtering with jQuery.grep  
I get it; some of these utility methods aren't nearly as exciting as working with AJAX and effects, but, nonetheless, if you learn them, you'll drastically improve the quality (and length) of your code.  
Today, we'll review the helpful $.grep method, which can be used to filter an array, based upon the results of a particular test.  

Day 23: Custom Events and the Observer Pattern  
We're not limited to jQuery's built-in events; we can create our own with ease! Additionally, we'll review the popular Observer Pattern (PubSub), and how it can provide increased flexibility for your projects.  

Day 24: Loading Pages Asynchronously  
We've put it off long enough; it's time to dig into jQuery's various AJAX helper methods. You're in luck, because this is an area where jQuery truly shines. It manages to wrangle all of those nasty browser inconsistencies into place, while providing us with a laughably easy-to-use API.  
  
Today, we start with the simplest of all the AJAX helper methods: load().  

Day 25: Interacting with the Server-Side  
The load() method is certainly helpful, but what if we need slightly more control? In this lesson, we'll take a step up, and review two more AJAX helper methods: $.get and $.post. These methods allow us to communicate with the server-side.  


Let's imagine that you need to asynchronously update a database. When combined with the necessary servers-side logic to query the database, $.post can handle this task with ease.  

Day 26: PHP and jQuery - Part 1  
To round out this chapter, we'll review the core $.ajax method - the one that's doing the brunt of the work, while those pesky helper methods, like getJSON, take all the credit!


Over the course of the next two lessons, we'll build a sample application from scratch. In part one, we'll focus exclusively on the PHP side: the structure, database access, etc. In part two, though, we'll switch over to the JavaScript, and AJAXify the application!

Day 27: PHP and jQuery - Part 2  
In the previous lesson, we focused exclusively on the PHP aspect of our little project. Today, we get to switch over to the JavaScript, and enhance the web site. We'll pay special attention to code structure, the AJAX method, and communicating with the server.  

Day 28: Deferreds  
Deferreds are a relatively new addition (as of version 1.5) to jQuery that allow us to register multiple callbacks for any number of asynchronous actions. I'll show you why they're important, and how to use them in your projects today!  

Day 29: Head First Into Plugin Development  
In this massive lesson, we'll dive into jQuery plugin development. Along the way, we'll review various best practices and techniques for providing the highest level of flexibility for the users of your plugins.  




===

lesson-12  
video crashes halfway through  
https://tutsplus.com/lesson/full-control-with-animate/?WT.mc_id=learnjquery  

lesson-16 - Your Questions Answered

lesson-17 - Quiz (not available)