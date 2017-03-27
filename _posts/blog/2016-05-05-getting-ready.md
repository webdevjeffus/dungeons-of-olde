---
layout: blog-layout
title: getting ready
full-title: Getting ready for company
category: blog_posts
description: "A blog post on the current state of "
keywords: "game development, tabletop game development, "
comments: true
permalink: /blog/getting-ready/
---

The _Dungeons of Olde_ site has come a long way in the past two weeks. Here's a quick rundown of what's been accomplished on the site so far.

## Site Development
This is where I've been putting most of my effort in the last couple of days. I've implemented several features which I consider essential to the online side of the _DoO_ user experience:

- **Printer-friendly pages.** I've set up a media query in the site's CSS that reformats the rules pages for printing. When you click the Print option in your browser, the version of the page your printer receives is formatted in a very readable two-column layout, with the header and footer removed, and white text on a black background. I considered presenting the rules as a .PDF, but this early in the development, the rules are being edited and tweaked every day, and formatting an attractive .PDF takes quite a bit of time. Letting your browser format each page of rules for readable, economic printing seems the best use of resources for now.

- **Domain name.** I've registered **dungeonsofolde.com** and set the site up at that URL. It's still hosted as a GitHub Pages site, but the ugly default URL is no longer necessary.

- **Favicon.** I know it's a little thing, but pages without a favicon (that tiny icon in the browser tab, next to the page title) always look very unfinished to me. The favicon I've implemented may not be permanent, but it's good enough for a game in development.

- **Comments.** This was the big one. The decision to create and deliver this site using Jekyll and GitHub pages has many advantages&mdash;site security, ease of maintenance, elimination of back-end programming. But using Jekyll has one major cost: as a static-site generator, Jekyll can't do live comments, which I see as essential to the success of this project. After researching possible solutions, I decided to use <a href="https://disqus.com/" target="_blank">Disqus</a>, which combines easy set-up and maintenance for the admin (me); convenient access for community members (you) via Facebook, Google+, and Twitter accounts without requiring a dedicated Disqus account or dungeonsofolde.com membership; and low cost (free, at this level of usage). Let's hope Discus is as good as I've been led to expect.

I still have a few cosmetic and UI improvements to make to the site&mdash;I want to clean up the URLs in the address bar, add some graphics, implement post tags, just to name a few. But the site already has its own domain name, user-friendly navigation, comments, and readable formatting both online and in print. I feel pretty comfortable declaring the _Dungeons of Olde_ website an MVP at this point.

## Game Development
The game itself is not quite at the minimum viable stage yet, but it's close. There are enough rules published now to handle hand-to-hand combat, with weapons or without. I have the first character cards and counters (which _DoO_ uses instead of character sheets) laid out, along with gear and loot cards; all that remains on that front is to convert them into .PDFs so that they can be downloaded and printed for play. Once those resources are available, I'll write a one-page, introductory version of the rules, and post that as well. At that point, the game will be playable, as long as all you want to do is have characters dress up in armor and whack each other swords and axes.

The next step after that will be ranged combat rules, which shouldn't be a major stretch now that hand-to-hand combat is in place. There's a whole bunch of stuff that has to come after that&mdash;skills, magic and spells, special cards for conveniently tracking groups of similar NPCs on a single card, and especially a live dungeon-generating system using dungeon tiles, cards, and dice to create adventure scenarios on the fly, just to name a few items on my todo list. I expect I'll write a post covering near-term development priorities for _DoO_ by the end of the weekend.

Check back soon, though. My hope is to have the existing game materials downloadable by Saturday, so you can try out hand-to-hand combat. If anyone's listening yet, I hope you enjoy what there is of _DoO_ so far.