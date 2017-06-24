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

<h5>Trivial Challenges</h5>
<p>It is generally not necessary to roll for <em>Trivial</em> challenges, unless the task involves a <a href="#scaling-challenges">scaling challenge</a>, <a href="#critical-outcomes">critical outcomes</a> are possible, or the gamemaster judges the situation to be extremely tense and dramatic. In all other circumstances, you can treat an attempt at a <em>Trivial</em> challenge as an automatic success.</p>

<h2 id="attempts" class="new-page">Attempts</h2>
<p>When a hero tries to overcome a challenge, he makes an <strong>attempt</strong>. An attempt always includes a <strong>check roll</strong>, which determines <em>whether</em> he succeeds at the task, and it may require an <strong><a href="#effect-rolls">effect roll</a></strong>, which determines the <em>degree</em> of that success.</p>
<p>Every attempt is made using <a href="{{site.baseurl}}/core-rules/characters/#stat-dice">stat dice</a> for the <a href="{{site.baseurl}}/core-rules/characters/#stats">Primary Stat</a> relevant to the nature of the challenge. For example, a challenge calling for brute force uses a hero's Brawn dice, while a challenge requiring courage uses his Nerve dice. For most tasks, there will be an applicable <a href="#skills">skill</a>, so the attempt will use the Check Stat for that skill. For example, a hero tries to find food in the wilderness, either hunting small game or gathering wild vegetation; he is using the Forage skill, which is based on the Savvy stat, so he'll roll his Savvy dice in the attempt.</p>

<h5 id="check-rolls">Check Rolls</h5>
<p>Success in an attempt requires a Check roll, in which the hero must roll equal to or above the <a href="#challenges">challenge rating</a> on two <a href="{{site.baseurl}}/core-rules/dice/#exploding-dice">exploding</a> <a href="{{site.baseurl}}/core-rules/characters/#stat-dice">Stat Dice</a>. A character with Brawn 8 attempting to lift a heavy portcullis (CR 12) would need to roll a 12 or better on 2d8!.</p>

<h6>Adjusting Check Rolls</h6>
<p>Certain skills, items or other circumstances may adjust the result of a Check roll. <a href="{{site.baseurl}}/core-rules/dice/#adjustments">Adjustments</a> may add to or subtract from the result of the Check roll, and are applied once only, after any exploding dice have been resolved.</p>
<p>Note that <a href="{{site.baseurl}}/core-rules/dice/#modifying-dice">Modifications</a> change the <a href="{{site.baseurl}}/core-rules/dice/#die-rank">Die Rank</a> of the dice to be rolled, and are applied <em>before</em> the dice are thrown. Adjustments, on the other hand, change the <em>result</em> of the roll, and are applied <em>after</em> the dice are thrown and totalled.</p>

<h6 id="success-failure">Success and Failure</h6>
<p>If the result of a character's check roll equals or exceeds the challenge rating of the task he's attempting, he has succeeded in that attempt. If the check roll is less than the challenge rating, the character has failed in his attempt. The margin between the challenge rating for the attempt and his check roll determines how many <strong>ranks of success or failure</strong> he achieves, which may affect the outcome of his attempt.</p>
<p>A check roll equal to the challenge rating, or exceeding it by 1 or 2, counts as one rank of success. For every three points by which the check roll exceeds the challenge rating, the character earns an additional rank of success. If the character's check roll is 1 or 2 below the challenge rating, he suffers one rank of failure. For every three points by which the check roll falls below the challenge rating, the character suffers an additional rank of failure.</p>

<h5 id="critical-outcomes">Critical Outcomes</h5>
<p>Check rolls which produce multiple ranks of success or failure may result in critical outcomes. It is up to the gamemaster to determine when critical outcomes will be applied; some GMs will use them on every attempt made by a hero or important non-player character, but other gamemasters may prefer to reserve them for highly dramatic moments in the adventure. Whenever the gamemaster applies a critical success or failure to an attempt by a hero, that hero may earn character points due to the "learning opportunity" presented by the unusual outcome, as indicated on the table below.</p>

{% include tables/critical-outcomes-table.html %}


<h6>Suggested Bonuses and Penalties for Critical Outcomes</h6>
<ul>
  <li><strong>Major bonus:</strong> Choose: Consumable materials not consumed; or useful or valuable materials recovered.</li>
  <li><strong>Minor bonus:</strong> Choose: Task takes half the usual time; half the normal materials consumed; or product is unusually beautiful, valuable or effective.</li>
  <li><strong>Simple success:</strong> Task succeeds, and any consumable materials are spent.</li>
  <li><strong>Simple failure:</strong> Task fails, and any consumable materials are lost.</li>
  <li><strong>Minor penalty:</strong> Choose: task takes twice the normal amount of time; task consumes twice the normal amount of materials; or tools or equipment are damaged, imposing -2 penalty on future attempts until damaged tools are repaired or replaced.</li>
  <li><strong>Major penalty:</strong> Choose: Failure damages or destroys the object of the attempt; tools or equipment are destroyed, making future attempts impossible until lost tools are replaced.</li>
</ul>

<p>When a critical outcome is indicated in an attempt by a player hero, the player should describe the nature of the success or failure, and choose a bonus or penalty from the suggestions above or suggest an alternative. Of course, the gamemaster has the authority to alter or overrule the player's suggestion according to the circumstances. For example, a hero scores a Solid Success (Rank 2) on his Disable attempt to pick the lock on the Duke's bedchamber, earning a minor bonus. Since he knows there are guards that patrol the residential wing of the Duke's manor, the player sugggests that the lock turns out to be nearly identical to one he's disabled in the past, so he's able to pick it in just a few seconds (half the normal time); the gamemaster feels the player's suggestion is appropriate to the circumstances, and allows it.</p>
<p>Alternately, if the player had suffered a Decisive Failure (Rank 2) on the same attempt, he'd take a minor penalty. The player suggests that one of his lockpicks became stuck in the lock, and he needed double the normal amount of time to free it. The gamemaster agrees that the pick became stuck in the lock, but before the hero has time to free it, he hears a guard approaching around the corner. The GM tells the hero he must choose one of three options: snap the pick off in the lock before hiding in a nearby alcove; leave the pick sticking out of the lock where it might noticed by the guard, but hiding himself in the alcove; or taking the time to free the lockpick, knowing that he'll be seen by the guard as he rounds the corner.</p>

<p>Critical successes and failures on combat checks are discussed in the <a href="{{site.baseurl}}/core-rules/combat/#combat-critical-outcomes">Combat rules</a>.</p>

<div class="ph-ins-50 tab-ins-33 cmp-ins-33 ftrm-mar">
<img src="{{site.baseurl}}/img/rivals-DavidLewisJohnson-250x216.jpg" srcset="{{site.baseurl}}/img/rivals-DavidLewisJohnson-400x345.jpg 400w, {{site.baseurl}}/img/rivals-DavidLewisJohnson-700x603.jpg 700w, {{site.baseurl}}/img/rivals-DavidLewisJohnson-1000x861.jpg 1000w" size="50vw" class="border-thin" alt="Rivals by David Lewis Johnson" title="Rivals - Public domain image by David Lewis Johnson">
</div>

<h6 id="opposed-attempts">Opposed Attempts</h6>
<p>A challenge that pits one character directly against another requires an <strong>opposed attempt</strong>. The character making the opposed attempt is called the <span id="instigator"><strong>instigator</strong></span>, while the character resisting the attempt is the <span id="target"><strong>target</strong></span>.</p>
<p>In an opposed attempt, each character rolls two <a href="{{site.baseurl}}/core-rules/dice/#exploding-dice">exploding</a> <a href="{{site.baseurl}}/core-rules/characters/#stat-dice">Stat Dice</a>. The target rolls first, and his result becomes the <a href="#challenges">challenge rating</a> for the instigator's Check roll. Then the instigator rolls. If the instigator's Check roll equals or exceeds the target's Check roll, the opposed attempt succeeds.</p>

<p>In <a href="#opposed-attempts">opposed attempts</a>, the <em>target's</em> Check roll is not subject to critical outcomes. This is because the target's Check sets the challenge rating (CR) for the instigator's Check roll, rather than being rolled against a CR of its own. The instigator's Check <em>is</em> subject to critical outcomes, though, and the gamemaster may rule that a critical failure (or success) by the instigator results in a bonus (or penalty) to the target, instead of a penalty (or bonus) to the instigator.</p>

<div class="no-break">
<h6 id="assisted-attempts">Assisted Attempts</h6>
<p>Certain challenges may allow for an ally to <strong>assist</strong> a hero attempting a challenge (instigator). The assistant makes a <a href="#check-rolls">Check roll</a> with a challenge Rating equal to the instigator's <a href="{{site.baseurl}}/core-rules/skills/#skills">Check Stat</a> for the Skill he's using in his Attempt. If the assistant's Check roll equals the instigator's Check Stat for the skill he's using, the instigator gets +1 on his Attempt. This bonus is increased by +1 for every <em>two</em> points by which the assistant's Check roll exceeds the instigator's Check Stat.</p>
</div>

<h6 id="scaling-challenges">Checks Against Scaling Challenges</h6>
<p>A <strong>scaling challenge</strong> occurs in circumstances where the character's doing especially well at the challenge may result in a quantifiably greater effect. A scaling challenge has a base challenge rank and rating, but for every additional challenge rank by which the character succeeds, he achieves greater success. Recall that each additional rank of success requires a margin of 3 points on the Check roll.</p>

<p>For example, if Briven had just a few seconds to gather usable arrows after a battle, the gamemaster might decide to handle the attempt as an Easy scaling challenge (CR 6) to Briven's Alertness skill, with each rank of success turning up three intact arrows. The player rolls Briven's Alertness Check using his <a href="{{site.baseurl}}/core-rules/skills/#skills">Check Stat</a>, Savvy, scoring an 11, so Briven recovers six arrows in all&mdash;three for the succeeding at the Easy level, and three more for also having met the Moderate challenge rating of 9.</p>




<h5 id="effect-rolls">Effect Rolls</h5>
<p>In some cases, a successful <a href="#check-rolls">Check roll</a> is followed by an <strong>effect roll</strong>, to determine <em>how effective</em> the success was. Effect rolls also use the character's Stat Die for the applicable <a href="{{site.baseurl}}/core-rules/skills/#skills">skill's Check Stat</a>. Depending on the circumstances, an effect roll may call for one, two, or more dice. Effect rolls are made with <a href="{{site.baseurl}}/core-rules/dice/#exploding-dice">exploding dice</a>, unless the rules specify otherwise.</p>

