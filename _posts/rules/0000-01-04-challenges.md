---
layout: rules-layout
title: challenges
full-title: Challenges
category: rules-core
description: "Rules for attempting difficult tasks in "
keywords: "rpg stats, rpg challenges, rpg rules, tabletop rpg rules "
---

<p id="challenges">Any task where there is a chance of meaningful failure is resolved as a <strong>Challenge</strong>. The difficulty of the Challenge is expressed by its descriptive Rank, and a number, called the <span id="challenge-rating"><strong>Challenge Rating</strong></span>, or <strong>CR</strong>.</p>

{% include tables/challenges-table.html %}

<p>When a hero tries to overcome a Challenge, he makes an <span id="attempt"><strong>Attempt</strong></span>. An Attempt always includes a <strong><a href="check-roll">Check Roll</a></strong>, which determines <em>if</em> he succeeds at the task, and may include an <strong><a href="effect-roll">Effect Roll</a></strong>, which determines the <em>degree</em> of that success.</p>
<p>Every Attempt is made using <a href="#stat-dice">Stat Dice</a> for the <a href="#stats">Primary Stat</a> relevant to the nature of the Challenge. For most tasks, there will be an applicable <a href="#skills">Skill</a>, so the Attempt will use the Check Stat for that Skill. For example, a Challenge calling for brute force uses a hero's Brawn dice, while a Challenge requiring courage uses his Nerve dice.</p>

<h5 id="check-rolls">Check Rolls</h5>
<p>Success in an Attempt requires a Check Roll, in which the hero must roll equal to or above the <a href="#challenges">Challenge Rating</a> on two <a href="#exploding-dice">exploding</a> <a href="#stat-dice">Stat Dice</a>. A character with Brawn 8 Attempting to lift a heavy portcullis (Challenge Rating 12) would need to roll a 12 or better on 2d8!.</p>

<h6>Adjusting Check Rolls</h6>
<p>Certain skills, items or other circumstances may adjust the result of a Check Roll. <a href="#adjustments">Adjustments</a> may add to or subtract from the result of the Check roll, and are applied once only, after all exploding dice have been resolved.</p>
<p>Note that <a href="#modifying-dice">Modifications</a> change the <a href="#die-rank">Die Rank</a> of the dice to be rolled, and are applied <em>before</em> the dice are thrown. Adjustments, on the other hand, change the <em>result</em> of the roll, and are applied <em>after</em> the dice are thrown and totalled.</p>

<h6 id="opposed-attempts">Opposed Attempts</h6>
<p>A <a href="#challenges">Challenge</a> that pits one character directly against another requires an <strong>Opposed Attempt</strong>. The character making the Opposed Attempt is called the <span id="instigator"><strong>Instigator</strong></span>, while the character resisting the Attempt is the <span id="target"><strong>Target</strong></span>.</p>
<p>In an Opposed Attempt, each character rolls two <a href="#exploding-dice">exploding</a> <a href="#stat-dice">Stat Dice</a>. The target rolls first, and his result becomes the <a href="#challenge-rating">Challenge Rating</a> for the Instigator's Check Roll. Then the instigator rolls. If the instigator's roll equals or exceeds the target's roll, the Opposed Attempt succeeds.</p>

<h6 id="assisted-attempts">Assisted Attempts</h6>
<p>Certain <a href="#challenges">Challenges</a> may allow for an ally to <strong>Assist</strong> a hero attempting a Challenge (Instigator). The Assistant makes a <a href="#check-rolls">Check Roll</a> with a Challenge Rating equal to the Instigator's <a href="#skills">Check Stat</a> for the Skill he's using in his Attempt. If the Assistant's Check Roll equals the Instigator's Check Stat, the Instigator gets +1 on his Attempt. This bonus is increased by +1 for every <em>two</em> points by which the Assistant's Check Roll exceeds the Instigator's Check Stat.</p>

<h6 id="scaling-challenges">Checks Against Scaling Challenges</h6>
<p>A <strong>Scaling Challenge</strong> occurs in circumstances where the character's doing especially well at the <a href="#challenges">Challenge</a> may result in a quantifiably greater effect. A Scaling Check has a Challenge Rank and Rating, but for every Challenge Rank by which the character succeeds, he achieves additional success. For example, if a hero had just a few seconds to gather usable arrows after a battle, the GM might decide to handle the attempt as an Easy Scalable Challenge (CR 6) to the Alertness skill, with each Rank of success turning up three intact arrows. The player rolls his Alertness Check using its <a href="#skills">Check Stat</a>, Savvy, scoring an 11, and recovers six arrows in all&mdash;three for the succeeding at the Easy level, and three more for also having met the Moderate Challenge Rating of 9.</p>

<h5 id="effect-rolls">Effect Rolls</h5>
<p>In some cases, a successful <a href="#check-rolls">Check Roll</a> is followed by an Effect Roll, to determine <em>how effective</em> the success was. Effect Rolls also use the character's Stat Die for the applicable <a href="#skills">Skill's Check Stat</a>. Depending on the circumstances, an Effect Roll may call for one, two, or more dice. Effect rolls are made with <a href="#exploding-dice">exploding dice</a>, unless the rules specify otherwise.</p>

