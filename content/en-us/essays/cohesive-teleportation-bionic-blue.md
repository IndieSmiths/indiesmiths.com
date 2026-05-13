authors: Kennedy Richard S. Guerra
author-urls: https://kennedyrichard.com
keywords: teleportation
          bionic blue
          game development
          game design
          writing
          game writing
description: Essay on how we made sure teleportation in the 2D platformer game Bionic Blue works well with the other elements of the game, not hindering the design, play or story/writing, helping the game world become more believable.
publish-date: 2026-05-13
include-comment-section: True

# Making teleportation cohesive in the Bionic Blue game

As an open-source maintainer with a few projects, it is not easy to find time to make all game elements cohesive. But, sometimes I have to risk not meeting specific deadlines in favor of making the game world just a tad more believable. Today I wanted to share how I tried to do this for the action of teleporting in and out of a mission area (level).

As seen below, the first thing that happens at the beginning of a mission is Blue teleporting into the mission's area. Notice the satellite dish near the spot where he lands.

<img class="mx-auto d-block" alt="Animated GIF showing Blue teleporting into the mission area next to a satellite dish." src="https://i.imgur.com/yC9XleP.gif" />

Throughout the mission area, Blue finds other satellite dishes and this is what happens when he touches them:

<img class="mx-auto d-block" alt="Animated GIF showing Blue reaching a new satellite dish in the mission area. After touching it, a label indicating it is a checkpoint is shown for a few seconds." src="https://i.imgur.com/qpMrfFC.gif" />

In other words, the dishes clearly serve as checkpoints.

This is reinforced whenever the mission restarts after Blue dies:

<img class="mx-auto d-block" alt="Animated GIF showing Blue traversing through the misison area, dying, then after the screen fades to black the mission restarts with Blue teleporting into the mission area next to a satellite dish." src="https://i.imgur.com/jeKOOlC.gif" />

This detail seems trivial, but think about it like this: if game characters could teleport in and out of a mission's area whenever and wherever they wanted, why wouldn't they do it to escape threats or to tactically teleport right next to an unsuspecting enemy?

That is why I thought it was important to make the act of teleporting dependent on specific spots and decided a satellite dish would be the perfect gizmo for that.

Also, only the first satellite dish is turned on when Blue enters the mission's area. This also explains why the character couldn't teleport right away to the boss area and has to advance through the level in order to activate the other satellite dishes, so that he can teleport closer to the objective the next time the mission restarts.

After defeating the boss, the character doesn't teleport away immediately either. Since teleportation is dependent on satellite dishes, Blue walks back just a little ways in order to access the satellite dish that lies just outside the boss area, which was also placed there in order for Blue to restart the mission just outside the boss area in case he was defeated by the boss.

<img class="mx-auto d-block" alt="Animated GIF showing Blue next to a defeated robot. Then he walks back to a satellite dish outside the boss building after going through a few gates and teleports out of the mission area." src="https://i.imgur.com/m8ncYpI.gif" />


## Final words

In conclusion, the existence and placement of satellite dishes as teleportation equipment serves not only game design purposes, but also the writing, helping make the world a tad more cohesive/believable.

As a bonus, I leave the following questions for you to reflect upon, something that I intend to address in a future write-up: what about the writing behind dying and restarting a mission? Is the character immortal? Does he goes back in time? Should the character ever acknowledge his own death? Is he even aware of it?

As always, I finish asking that you consider supporting the project. You can find links to [Patreon](https://patreon.com/KennedyRichard), GitHub [sponsors](https://github.com/sponsors/KennedyRichard) and other additional services like those [on this page](https://indiesmiths.com/donate).
