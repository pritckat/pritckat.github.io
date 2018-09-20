---
layout: post
title:      "Overwatch Teams Library: A Sinatra Debut"
date:       2018-09-20 19:45:55 +0000
permalink:  overwatch_teams_library_a_sinatra_debut
---


Ladies and gentlemen, I've stumbled through another project. I'm starting to wonder if all projects end at the point where one throws their hands up in the air and resigns themselves to the fact that they aren't entirely happy, but technically they've accomplished everything they set out to do. Which is what has happened for me. This post is going to be partially devoted to my analysis of the process I went through creating my Overwatch Team Library and mostly devoted to a list of other features I've thought of that I'd like to add in the future. Reader, if you find this list and glance at my repository and note that I've added one of these, would you briefly, quietly congratulate me? It will mean I have grown as a person.

Everything began with the best of intentions on my part. Fresh from my confused approach to my CLI project and even fresher from my more confused approach to Fwitter I approached my initial concept of creating a sort of social media site for people to store their team composition preferences and player character preferences. Perhaps, you already know this isn't what I made. In the initial planning stages of crafting this site, I stumbled upon the bones of it, a simple team creator site for people to share ideas for team compositions. A lightbulb self-illuminated above me. I was sure I knew how to complete all the components of that site already, and it would be greatly useful for my teammates and I who constantly forget what characters we like to combine in our Overwatch matches. I was excited to make something I would use.

I knew from preparatory labs that having all of my goals written out in the order I wish to accomplish them lowers my stress and clarifies my process. So I got out a notebook and listed my models, tables, views, and associations. When I inevitably deviated from the initial plan, the notebook at least served to soothe me. And I could destress by crossing things out and frowning.

Next, I set out to conquer my fear of ActiveRecord and create my tables, models, and associations. Something about ActiveRecord felt too behind the scenes to me. It secrets through my code mystically making my life easier. Naturally, I didn't trust it. Fortunately, I slowly got a handle on its machinations. I learned my difficulties with it stemmed from never saving instances of my models to my database, misspellings, not understanding what "cache" means... etc. Now I feel that while I don't understand every method ActiveRecord gives me, I know how to look them up and I know how to debug my problems with it. I even know how to require the Gemfile.

Then, I moved on to creating my users and letting them log in and out. When I worked on my CLI project, I started with the user experience, and that didn't seem like a terrible starting place for my Sinatra project. So I made an index page, assigned myself a metaphysical identity of "user" and asked myself what I wanted to see, what I wanted to do. Using this process, I filled out my user pages and eventually my team pages until I felt I had a site that one could navigate comfortably and gave the information that I required. It was nice, after the ActiveRecord portion, to feel comfortable coding. This natural process was a bit of a break in my coding experience. I had a little fun, adding methods to my classes, like team_composition that would allow me to see what roles on each team were filled. I also added information validation in my forms and controllers and was thrilled with how simple it was to make all teams have a name or all teams have six characters. This was the most fun part of the project for me.

Once I had a working site, I moved into the security portion. With a few helper methods, this part didn't prove too much of a challenge. I had already given my user a hashed and salted password and now all that was left was to enable sessions and then add some redirects. I had no idea how to alert the user as to why they were being redirected, but from some searching, I found that one can put error messages right in the URL of the redirect. This was probably the most useful and exciting thing I learned that was entirely new to me in this whole project. It made my life much easier than I thought it would be.

Finally, I had my boyfriend test out my site, building teams and trying to meddle in places he didn't belong. At that point I started thinking about what else I could add and reached the scenario illustrated in the introduction. My site worked, my project was ready for submission. I will hopefully come back and make branches and add features that occured to me during the site building. For now those ideas will live here:

* add maps to the site and the ability to tag certain team comps as being good on certain maps
* add the ability to view teams by composition
* add the ability to view teams that include select characters
* add a random team creator
* add the ability to save a copy of another user's team for yourself, to find easier later or to revise

That is all for now. Thank you for reading.
If you'd like to view my site, I include a link for the repository here: https://github.com/pritckat/sinatra-project.git
