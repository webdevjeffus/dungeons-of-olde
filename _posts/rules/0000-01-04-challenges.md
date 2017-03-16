---
layout: rules-layout
title: challenges
full-title: Challenges
category: rules-core
description: "Rules for attempting difficult tasks in "
keywords: "rpg stats, rpg challenges, rpg rules, tabletop rpg rules "
permalink: /core-rules/challenges/
---

<div class="ph-col-12">
<img src="{{site.baseurl}}/img/potionmaker-JoyceMaureira-400x198.jpg" srcset="{{site.baseurl}}/img/potionmaker-JoyceMaureira-800x395.jpg 800w, {{site.baseurl}}/img/potionmaker-JoyceMaureira-1200x592.jpg 1200w" class="border-thin" alt="An alchemist preparing potions" title="Potionmaker - Public domain image by Joyce Maureira">
</div>


<h2 id="challenge-rating">Challenge Ratings</h2>
<p>Any task where there is a chance of meaningful failure is resolved as a <strong>challenge</strong>. The difficulty of the challenge is expressed by its descriptive <strong>challenge rank</strong>, and a number, called the <strong>challenge rating</strong>, or <strong>CR</strong>.</p>

{% include tables/challenges-table.html %}

<h2 id="attempts">Attempts</h2>
<p>When a hero tries to overcome a challenge, he makes an <strong>attempt</strong>. An attempt always includes a <strong>check roll</strong>, which determines <em>whether</em> he succeeds at the task, and it may require an <strong><a href="#effect-rolls">effect roll</a></strong>, which determines the <em>degree</em> of that success.</p>
<p>Every attempt is made using <a href="{{site.baseurl}}/core-rules/characters/#stat-dice">stat dice</a> for the <a href="{{site.baseurl}}/core-rules/characters/#stats">Primary Stat</a> relevant to the nature of the challenge. For most tasks, there will be an applicable <a href="#skills">skill</a>, so the attempt will use the Check Stat for that skill. For example, a challenge calling for brute force uses a hero's Brawn dice, while a challenge requiring courage uses his Nerve dice.</p>

<h5 id="check-rolls">Check Rolls</h5>
<p>Success in an attempt requires a Check roll, in which the hero must roll equal to or above the <a href="#challenges">challenge rating</a> on two <a href="{{site.baseurl}}/core-rules/dice/#exploding-dice">exploding</a> <a href="{{site.baseurl}}/core-rules/characters/#stat-dice">Stat Dice</a>. A character with Brawn 8 attempting to lift a heavy portcullis (CR 12) would need to roll a 12 or better on 2d8!.</p>

<h6>Adjusting Check Rolls</h6>
<p>Certain skills, items or other circumstances may adjust the result of a Check roll. <a href="{{site.baseurl}}/core-rules/dice/#adjustments">Adjustments</a> may add to or subtract from the result of the Check roll, and are applied once only, after any exploding dice have been resolved.</p>
<p>Note that <a href="{{site.baseurl}}/core-rules/dice/#modifying-dice">Modifications</a> change the <a href="{{site.baseurl}}/core-rules/dice/#die-rank">Die Rank</a> of the dice to be rolled, and are applied <em>before</em> the dice are thrown. Adjustments, on the other hand, change the <em>result</em> of the roll, and are applied <em>after</em> the dice are thrown and totalled.</p>

<div class="ph-ins-50 tab-ins-33 cmp-ins-33 ftrm-mar">
<img src="{{site.baseurl}}/img/rivals-DavidLewisJohnson-250x216.jpg" srcset="{{site.baseurl}}/img/rivals-DavidLewisJohnson-400x345.jpg 400w, {{site.baseurl}}/img/rivals-DavidLewisJohnson-700x603.jpg 700w, {{site.baseurl}}/img/rivals-DavidLewisJohnson-1000x861.jpg 1000w" size="50vw" class="border-thin" alt="Rivals by David Lewis Johnson" title="Rivals - Public domain image by David Lewis Johnson">
</div>

<h6 id="opposed-attempts">Opposed Attempts</h6>
<p>A challenge that pits one character directly against another requires an <strong>opposed attempt</strong>. The character making the opposed attempt is called the <span id="instigator"><strong>instigator</strong></span>, while the character resisting the attempt is the <span id="target"><strong>target</strong></span>.</p>
<p>In an opposed attempt, each character rolls two <a href="{{site.baseurl}}/core-rules/dice/#exploding-dice">exploding</a> <a href="{{site.baseurl}}/core-rules/characters/#stat-dice">Stat Dice</a>. The target rolls first, and his result becomes the <a href="#challenges">challenge rating</a> for the instigator's Check roll. Then the instigator rolls. If the instigator's Check roll equals or exceeds the target's Check roll, the opposed attempt succeeds.</p>

<h6 id="assisted-attempts">Assisted Attempts</h6>
<p>Certain challenges may allow for an ally to <strong>assist</strong> a hero attempting a challenge (instigator). The assistant makes a <a href="#check-rolls">Check roll</a> with a challenge Rating equal to the instigator's <a href="{{site.baseurl}}/core-rules/skills/#skills">Check Stat</a> for the Skill he's using in his Attempt. If the assistant's Check roll equals the instigator's Check Stat for the skill he's using, the instigator gets +1 on his Attempt. This bonus is increased by +1 for every <em>two</em> points by which the assistant's Check roll exceeds the instigator's Check Stat.</p>

<h6 id="scaling-challenges">Checks Against Scaling Challenges</h6>
<p>A <strong>scaling challenge</strong> occurs in circumstances where the character's doing especially well at the challenge may result in a quantifiably greater effect. A scaling challenge has a challenge rank and rating, but for every challenge rank by which the character succeeds, he achieves additional success.</p>

<p>For example, if a hero had just a few seconds to gather usable arrows after a battle, the gamemaster might decide to handle the attempt as an Easy scaling challenge (CR 6) to the hero's Alertness skill, with each rank of success turning up three intact arrows. The player rolls his Alertness Check using its <a href="{{site.baseurl}}/core-rules/skills/#skills">Check Stat</a>, Savvy, scoring an 11, and recovers six arrows in all&mdash;three for the succeeding at the Easy level, and three more for also having met the Moderate challenge rating of 9.</p>

<h5 id="effect-rolls">Effect Rolls</h5>
<p>In some cases, a successful <a href="#check-rolls">Check roll</a> is followed by an <strong>effect roll</strong>, to determine <em>how effective</em> the success was. Effect rolls also use the character's Stat Die for the applicable <a href="{{site.baseurl}}/core-rules/skills/#skills">skill's Check Stat</a>. Depending on the circumstances, an effect roll may call for one, two, or more dice. Effect rolls are made with <a href="{{site.baseurl}}/core-rules/dice/#exploding-dice">exploding dice</a>, unless the rules specify otherwise.</p>

