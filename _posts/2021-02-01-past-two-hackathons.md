---
layout: post
title: What We Built In The Last Two Hackathons
subtitle: Get more out of Google search, generate a fun meal, and a bonus project
gh-repo: stevestar888/
gh-badge: [follow]
tags: [hackathon, side-project, fun]
comments: true
---

Here is what some friends and I made during the last two hackathons. “It’s not much, but it’s honest work.” 

## Google Power Search (June 2020 during Hack the Northeast)
Nearly everyone uses Google to search the web, but there are actually some modifiers you can use to further refine your search. For example, putting `filetype:pdf` after your query will yield you results that are only PDFs. Similarly, putting `“minecraft update 1.18”` after your query will show results that explicitly have “minecraft update 1.18”. So, in essence, we built a GUI that lets you use the advanced operators without having to remember them. 

As you type in the text boxes / select for filetype, your Google search string is automatically generated. So, then, click the colorful search icon or press enter. While we didn’t include all operators, I think we covered most of the frequently used ones. Now, because I’m more familiar with the search operators, I’ll just manually type `filetype:pdf` or `site:reddit.com` because it rolls off the hand, but I find myself circling back to this for more involved searches.

[See the site](http://google-power-search.rf.gd) for yourself, [view the submission](https://devpost.com/software/powerful-google-search) on devpost, or [inspect the code](https://github.com/stevestar888/google-power-search) behind it.


## Bowdoin "Fun" Menu (February 2021 during Texas A&M’s hackathon)
Here, we realized there wasn’t enough “disruption” in the dining hall menu display space, so we took a stab at building something better. Originally, my idea was we’d pull the menu off Bowdoin’s website every day and you could sign up to get alerts if _______  was on the menu. You could choose to get a sms or email notification telling you which dining hall and which meal. We didn’t end doing this. 

Instead, we made our own display and added a feature to “get a fun meal,” which just randomly chooses a food from each food category 😂! The hardest part was actually trying to reverse engineer the menu API. At first, we were going to scrape the website, but Josh found a file literally called `dining-menu.js` and it sent a post request to a specific url. All we had to do was figure out the parameters, which was a bunch of educated guess-and-check.

[See the site](http://bowdoin-menu-app.rf.gd) for yourself, [view the submission](https://devpost.com/software/dining-hall-meal-maker) on devpost, or [inspect the code](https://github.com/stevestar888/bowdoin-menu-app) behind it.

## Bowdoin Facility Hours (Spring 2020 for the Human-Computer Interaction class)
After doing a bunch of brainstorming and needfinding, we found our technical abilities and peoples’ needs intersected at a web app that acts as one central place to find hours for common Bowdoin facilities. We found many people, to find the hours for a building, would search “Bowdoin _______ hours”. If, instead, they had our site bookmarked, finding the hours would take a few less steps and should be faster as well.

In hindsight, HCI was a really cool class. And you learn so much practical Front-end developer knowledge…

[See the site](http://bowdoin-facility-hours.surge.sh/) for yourself. (No github because it was a school project.)