--
layout: post
title: "Remembering how I put this together"
--

# This is my first website

It's built with Jekyll on Github Pages; I alter it by changing the
root files on my computer, checking that locally with 'bundle exec
jekyll serve' and then commiting my work to github.

Every now and then I should do 'bundle update github-pages' I think.
This is how I keep everything up to date. I'm pretty sure.

(Some stretch goals for my
site)[https://www.smashingmagazine.com/2017/04/jekyll-wordpress-developers/]

(more
basic)[http://jmcglone.com/guides/github-pages/#:~:text=GitHub%20Pages,-GitHub%20Pages%20are&text=GitHub%20users%20can%20create%20and,file%20like%20any%20other%20website.]

The things that I still need to figure out how to do:
 - make a favicon
 - make my work more accessible visually
 - reckon with myself over my use of analytics
 - fix the broken link to oregon laws (any others?)

 - enforce HTTPS
 - set up my site at the apex domain
  - both of these will require altering my \_config.yml and google
    analytics, along with the links to my work embedded in my site

Stretch goals
 - make a site image, and a personal profile/banner sort of image that
   pokes fun at the whole hacker thing
 - make the site less grippingly basic

Questions I've got
 - am I using the general format right? how do I make blog posts and
  make them link to each other nicely?
 - why are my commits coming from an account that's not actually
   logged in as committing and how can I change that/obscure it?
 - how do you safely put an email out on the web without wrecking it
   forever?


   FAVICON
   - while there is content on it which is in the \_includes/header,
     that should actually be in \_includes/head, none of this is
     working and the only thing that actually worked was putting it in
     \_layout/default, which is weird and I'm confused by.
