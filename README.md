Frontman Challenge
==================

* Challenge time: Friday afternoon (+ weekend if you need it)
* Use everything you need but copy-pasting code from Twitter.com is cheating! However, feel free to inspect its HTML, JS and CSS code.


Challenge:
-------

Reimplement the Twitter.com feed page as close as possible to the real look and feel. This is what a Twitter feed page looks like: 

![screenshot](/images/screenshot.png)

You will need a Twitter account to do this task because you'll be inspecting the structure of the real Twitter feed to understand how it's done.

The goal of this exercise is to test your front-end skills. Don't worry about the backend at all. You are expected to produce only HTML, CSS and JS files. Do not build a Sinatra application. The resulting file should look as close to the real Twitter feed as possible.

Goal 1 
-------

Make sure it looks good on the desktop. As a minimum you should have the header and the list of tweets.

__Tip__: You don't have to use exactly the same CSS techniques as Twitter developers did. For example the home icon in the header is loaded as a sprite but it may be easier to do it using just an img tag.

__Another tip__: play with the page a lot before starting coding it. Notice how the header stays in a fixed position as you scroll the page. Notice that there's no footer because of infinite scrolling.

Goal 2
-------

Add JavaScript for infinite scrolling (using dummy data, no server-side at all), expanding the tweet input box on focus and, if you're feeling adventurous, a popup to add a new tweet.

Don't forget the infinite scrolling adds a spinner to show that data is being loaded. Even though you'll be using dummy data, emulate the delay.

Goal 3
------

Make it responsive. Notice that Twitter has very few responsive features other than resizing the search box and hiding the labels in the navigation bar. 

There's no definite pass/fail mark in this exercise. Rather, the teachers will use their best judgement to decide if the page really does look and feel like Twitter.

Good luck :)
