---
layout: post
title:      "On Not Always Learning What I Expect To"
date:       2018-10-24 02:16:36 +0000
permalink:  on_not_always_learning_what_i_expect_to
---


Hubris. We learned about it in English classes. I faced it throughout this entire project. I'm not entirelysure why the ability to generate massive amounts of code with a single line in the terminal would cause someone such egotism, but here I am, humbled. Rails isn't terribly different from Sinatra, I thought. Rails is, perhaps, even easier. Well, no. With more power, came more ambition and less patience. This is my story. 

You'll, perhaps, be unsurprised to find that this is my second attempt at a rails app. The first was quit in a rage. Having somewhat breezed through all the lessons, it was not till I was faced with the (somewhat) blank text editor that I realized I didn't actually know how to code with Rails. At least, I didn't really know how to use any of my tools that were new from Sinatra. Over and over, I would scour my old code for answers for simple things. How to set up a before action. How to use form_for. I even forgot what a helper was. A solid two hours were spent relearning which parts of my code can "see" which other parts. It was difficult to accept that the project I thought would be over quickly was to take much longer than anticipated. And in a huff, I gave up some of my loftier ambitions. In a second huff, I scrapped the whole thing, deciding I wasn't capable of installing key features.

A miraculous and unexpected thing comes with quitting. I spent a day letting all my failures and re-readings percolate while I dabbled in JavaScript. And I let my newfound humility work on my expectations. Slowly, the general form Rails apps take clicked for me. I felt like I finally understood the need for partials and helpers. I even accepted that using Active Record Query methods was simpler and more efficient than writing much longer Ruby scripts to accomplish the same task. Renewed, I re-entered the ring. With a clearer mind, with a humbler mind, and with more patience, I started my second project.

And the second time still was not easy. I'm proud of my search feature, a far bit more legible than the one I wrote in lessons (with no clumsy, useless if's). I'm pleased with the ease with which I managed to get errors to show up and the little task bar I put at the top. But I have my misgivings. You'll notice there is a controller for genres, but it's empty. I wanted my genres to act similarly to Twitter hashtags, but ran out of time. And maybe you'll notice the entirely unused favorite boolean added to the authors table. It's there from when I didn't realize I'd need a join table to make authors favorite-able(sp?). I keep it as a reminder to come back and add more features.

Primarily, I am discontent with my app's organization. I know when I can use a helper, but I use them more for increased legibility than to avoid repeating myself. And I have many methods in my controllers, but I have no clue how to put them into my models or anywhere else. The redirects and params invocations made it seem easier to use a private section of my controller. Organization has never come naturally to me and I'm hoping to learn this better through coding with others.

All in all, I have the same bittersweet reaction to calling this project finished (for now) that I have for all my other projects. This one ended before I was truly happy with it, but I feel it is important to respect self-inflicted deadlines and I did, technically, fulfill all the requirements. For that I am glad.

More, this project, I feel I learned what it's like to naively overestimate one's own understanding. It was really nice feeling comfortable with my skill and somewhat devastating having my comfort all stripped away, slowly; knowing I had grown complacent to learn passively. Coming out of the project, I enjoy feeling I learned and I especially enjoy knowing I will be naive and face my own hubris again, this time perhaps more prepared to fail and grow once more.

If you'd like to check out my repo, it's here: https://github.com/pritckat/book_loaning_app.git

As always, thank you for your interest in my journey.
