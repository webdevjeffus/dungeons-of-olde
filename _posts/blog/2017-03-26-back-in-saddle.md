---
layout: blog-layout
title: back in the saddle
full-title: Back in the Saddle Again
category: blog_posts
description: "A blog post on the current state of "
keywords: "game development, tabletop game development, "
comments: true
permalink: /blog/back-in-the-saddle/
---

<div class="ph-ins-50 tab-ins-50 cmp-ins-50 hdrm mar-l ftrm-mar first-img">
  <img src="{{site.baseurl}}/img/pd-knights-in-battle-250x181.jpg" srcset="{{site.baseurl}}/img/pd-knights-in-battle-400x289.jpg 400w, {{site.baseurl}}/img/pd-knights-in-battle-700x506.jpg 700w, {{site.baseurl}}/img/pd-knights-in-battle-900x650.jpg 900w" size="50vw" class="border-thin" alt="Knights battle with lances" title="Knights in battle - Vintage image in the public domain">
</div>It's been several months since I've posted to this blog, and a lot has happened since then. Let me catch you up...

Right after my posts in the first week of May, 2016, a close family member had a major health crisis that resulted in an extended hospital stay, followed by several months of rehabilitation. For most of the spring, summer and fall of 2016, caring for that loved one took over our lives, and projects like _Dungeons of Olde_ fell to the bottom of the priority list.

In December of 2016, I turned back to the game and the website, making some tweaks to the code, and finished out the first draft of the rules for actions and combat. Then the game was back-burnered again while I overhauled my professional website and expanded my portfolio in January and February, but I found a bit of time to read over the rules and do some solo playtesting around the edges. Once the renovated version my site at webdevjeff.us was deployed, I was finally able to turn back to _Dungeons of Olde_ in a serious way.

## Rules Evolution
My first priority in the current sprint was to get a playable alpha set of rules deployed, so the game could get some real playtesting. Over the last several months, my vision for the game evolved away from a gamemaster-optional dungeon crawl, toward a full-but-flexible fantasy RPG. To that end, I dropped any references to pre-programmed scenarios, rotating monster-wrangler duties, and other accomodations for play without a gamemaster. Instead, I completed a complete overhaul of the rules of the game, focusing on getting a real "minimum viable product" version of the core mechanics available.

### Core Rules
The result of that effort can be seen in the [Core Rules]({{site.baseurl}}/core-rules/) pages, which can be found at the beginning of the Rules section of the website. I've managed to boil the core mechanics of the game down to seven web pages, which print out to about 15 letter-size pages of rules, including tables, illustrations, and white space. The rules are currently sufficient to let you create and equip non-spellcasting characters and have them fight one another, up close or at range, as well as attempt non-combat tasks like lock-picking, tracking, and telling lies.


At the moment, the prior version of the rules are still available, in all the sections that _follow_ the Core Rules pages in the general [Rules]({{site.baseurl}}/rules/) section. These older rules will be rolled into the expanded, optional rules that are intended to supplement the Core Rules, but in many ways, the Core Rules have moved away from them as they stand currently. If you are interested in incorporating them into your playtesting, expect there to be conflicts between these older rules and the Core Rules; when you encounter such differences, the Core Rules supercede the other sections.

<div class="ph-ins-33 tab-ins-33 cmp-ins-33 hdrm ftrm">
  <a href="{{site.baseurl}}/resources/miniatures/">
    <img src="{{site.baseurl}}/img/doo-stairs-free-250x188.jpg" srcset="{{site.baseurl}}/img/doo-stairs-free-400x301.jpg 400w, {{site.baseurl}}/img/doo-stairs-free-700x527.jpg 700w" size="50vw" class="border-thin" alt="The Dungeons of Olde tile system" title="Check out the Dungeons of Olde tile system">
  </a>
</div>

### Enhanced Resources
I've added several [reference sheets]({{site.baseurl}}/resources/sheets/), that collect all the tables, along with summaries of key rules, on pages which can be easily printed for use during play. These can be found in the Resources section of the website, along with a first-draft _Dungeons of Olde_ character sheet and two sample characters. These character and reference sheets should make it possible to playtest the basic combat machanics in the _Dungeons of Olde_ Core Rules.

In addition to the new character and reference sheets, the Resources section of the site now includes the core elements of the [_Dungeons of Olde_ miniature terrain]({{site.baseurl}}/resources/miniatures/ "Dungeons of Olde tile system") tile system. Presented as downloadable .pdf files, the _Dungeons of Olde_ terrain is a printable papercraft tile system, allowing you to create an infinite supply of modular dungeon terrain using your inkjet printer, cardstock, and optional dollar-store foamcore board. These tiles are designed to be simple to assemble, and inexpensive to produce, and compatible with any RPG or skirmish rules system that uses miniatures.

### Coming Soon
My very next task in developing the _Dungeons of Olde_ rules is to provide stats for a small selection of classic dungeon monsters, so that playtesters will have something for their aspiring heroes to kill! When those are ready, they'll appear in a bestiary or creature compendium accessible from the [Sourcebooks]({{site.baseurl}}/resources/sourcebooks/) page in the Resources section. Like the rest of the _Dungeons of Olde_ rules, this monster collection will be presented as a webpage with special, print-only formatting for convenient printing directly from your browser.

After that, I'll get to work on the magic system. I've got notes on a system that uses the basic mechanics of the _Dungeons of Olde_ stat, skill, and challenge rules to create a magic system that is both simple and flexible. My sense is that it's going to be one of the most interesting and unique aspects of the game, and I'm excited to get a presentable draft together for you to see. The basic version of this system will appear as a new page in the [Core Rules]({{site.baseurl}}/core-rules/ "Dungeons of Olde Core Rules index"), and an expanded version will eventually be a separate, optional rules "plugin."

Once we have some monsters and magic available, I plan to put the core system through a period of playtest. My goals for the _Dungeons of Olde_ rule system is that it be <em>consistent</em>, with key mechanics that work the same throughout the game; <em>flexible</em>, with rules that handle a wide variety of anticipated as well as unanticipated situations; and <em>elegant</em>, with exactly the right amount of rules to handle most roleplaying scenarios, with minimal gaps and no bloat. Rules systems that meet these three goals are both easy to learn and smooth to play, but only playtesting will reveal if _Dungeons of Olde_ delivers on any or all of them.

## Site Development
I've also done a lot of work overhauling the [Jekyll code](https://github.com/webdevjeffus/dungeons-of-olde "Dungeons of Olde repository on GitHub") that generates the site. Most of these changes are under the hood, but they make the site more responsive&mdash;which is good for you&mdash;and easier to maintain and expand&mdash;which is good for me. Every minute I don't have to spend refactoring code or duplicating edits across multiple pages is another minute I can spend on developing the _Dungeons of Olde_ rule system.

I won't bore you with a lot of web-dev talk here, but I will mention a couple of things that any user of the site can see. First, I've added responsive illustrations to the pages in the Core Rules section. The site serves versions of each illustration in several resolutions, along with code that guides your browser in choosing the best version for your device, so that large screens on fast connections will enjoy hi-res versions, and while mobile devices on 4G or wireless won't have to download files far larger than they can display.

I'm also about 90% through the process of moving all of the game's data&mdash;all the numbers and notes in the tables you see throughout the rules&mdash;out of the text and into separate data files. This essentially turns the site into a small database, accessed through what Jekyll calls "includes"&mdash;small HTML templates coded to display the exact subset of the data needed for the current purpose. These data files and templates can be inserted into any page in the site, and when one of them is edited, that change is automatically made anywhere in the site that references the edited data or displays the updated template. This not only makes the site easier to maintain, but also means that when I make a change to the game data in one place, the entire game updates to reflect that change. It also explains why so much of the rules are now shown in tables, rather than paragraphs.

Going forward, I'll talk more about the technical side of the development process in [my professional blog](http://webdevjeff.us/blog/ "webdevjeff.us"), and reserve this _Dungeons of Olde_ blog for matters relating to the development of the game system.


