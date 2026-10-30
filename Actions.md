Table of Contents
=================

### General
- [Jumping](#jumping)
- [Running](#running)
- [Ducking](#ducking)
- [Carrying](#carrying)
- [Buttjump](#buttjump)
- [Backflip](#backflip)
- [Swimming](#swimming)
- [Sliding](#sliding)

### Power-Ups
- [Egg](#egg)
- [Fire Flower](#fire-flower)
- [Ice Rosette](#ice-rosette)
- [Air Flower](#air-flower)
- [Rock Shroom](#rock-shroom)
- [Star](#star)
- [Tux Doll](#tux-doll)

### Proposed
- [Super-Butt-Jump](#super-butt-jump)
- [Blowflyer](#blowflyer)
- [Flapping](#flapping)
- [Diving](#diving)


General
=======

Jumping
-------

![](images/jump.gif)

Jumping is the most basic ability present in platformers. A jump will allow Tux to reach
four tiles in height. A running jump reaches five tiles in height.

Running
-------

![](images/run.gif)

Running is an automatic action that gets activated when Tux is walking in the same direction
for a certain amount of time.

Milestone 1 used a dedicated RUN key, since Milestone 2 it is automatic.

Ducking
-------

![](images/duck.gif)

Ducking can be used to slide down small, one tile high holes as big Tux or to avoid projectiles
which are shot one tile above ground.

Carrying
--------

![](images/carry.gif)

Walking into or standing next to [carriable objects](https://github.com/SuperTux/supertux/wiki/Objects#Carriables)
while holding the *ACTION* key allows Tux to carry the object around. Releasing the *ACTION* key while walking results
in Tux throwing the object. Doing so while standing still results in Tux simply dropping the object right next to him.

Buttjump
--------

![](images/buttjump.gif)

A buttjump allows Tux to crush boxes from above and destroy some badguys that cannot be harmed
by a normal jump. To perform the buttjump, jump and hold down the *DOWN* key while in the air.

It takes Tux a small amount of time to jump back onto his feet upon touching the ground.

Backflip
--------

![](images/backflip.gif)

The backflip is a special jump which gives Tux some extra height compared to a normal jump.
It is performed while ducking and pressing the *JUMP* key.

Swimming
--------

![](images/swim.gif)

When in water, Tux can move and turn in all directions with his movement speed being momentum based.

Instead of jumping, Tux will gain a boost which lets him swim much faster.

Sliding
-------

While Tux is running, the player can press the DOWN key and slide. While sliding, Tux will get on his
belly and slide speedy down hilly terrain. Terrain that is formed like a ramp allows Tux to make
large jumps, which would be impossible without the slide action. While sliding downhill Tux will defeat
most enemies in his path, however enemies such as Snowman, Mr. Tree, and Spiky are not defeated and
instead will harm Tux.

Sliding did not exist as an action before SuperTux v0.7.0.

Crawling
--------

Crawling allows Tux to duck and avoid dangers from above, yet still move around. Crawling is only possible
for Big Tux. It is achieved mainly by ducking and then pressing the RIGHT or LEFT keys, but it will also
be activated when Tux slides and the slide speed wears off.

Crawling did not exist as an action before SuperTux v0.7.0.

---

Powerups
========

Egg
---

![](https://github.com/SuperTux/supertux/blob/master/data/images/powerups/egg/egg.png?raw=true)

The **egg** is the first and most vital powerup Tux encounters on his journey,
turning him into Big Tux. He now can take one more hit before dying, break wooden
crates by jumping against them, and perform actions such as the buttjump and backflip.

Fire Flower
-----------

![](https://github.com/SuperTux/supertux/blob/master/data/images/powerups/fireflower/fire_flower-0.png?raw=true)

The **Fire Flower** gives Tux the ability to shoot bouncing fire bullets that kill
most badguys in his path. It can also be used to melt the ice around frozen enemies,
making them active again.

Ice Rosette
-----------

![](https://github.com/SuperTux/supertux/blob/master/data/images/powerups/iceflower/ice_flower-0.png?raw=true)

The **Ice Rosette** (previously called Ice Flower) gives Tux the ability to shoot ice bullets.
These will not bounce the same way fire bullets will. When the ice bullet hits an enemy,
it will freeze him for a short time, if the enemy is actually freezable.

While frozen, enemies may be picked up and stood on, like rocks. They can be defeated
by buttjumping, but the ice will eventually melt, activating them.

- Perhaps the ice bullet could freeze water, bouncing across the
  surface of a body of the aforesaid liquid and freezing the surface
  of the **one block** it touches, and maybe one block either side of it.

Air Flower
----------

![](https://github.com/SuperTux/supertux/blob/master/data/images/powerups/airflower/air_flower-0.png?raw=true)

The **Air Flower** grants Tux the ability to jump higher and run faster.
Additionally, holding down the JUMP while in the air will allow Tux to glide,
allowing him to reach areas that he could not have reached without gliding.

Rock Shroom
------------

![](https://github.com/SuperTux/supertux/blob/master/data/images/powerups/earthflower/earth_flower-0.png?raw=true)

The **Rock Shroom** (previously called Earth Flower) gives Tux the ability to turn into
a rock and roll around by walking and pressing the DOWN key. As long as the player is
holding the DOWN key down, then Tux will stay in his rock form. While Tux is in rock
mode, he is invulnerable to most types of damage.

In older versions of the game, Tux could instead turn into a statue of himself for a short
time, being invincible to all types of danger. However, Tux would not be able to move while
in statue form. In, dark areas the rock shroom would also provide a small cone of light.

Star
----

![](https://github.com/SuperTux/supertux/blob/master/data/images/powerups/star/star-0.png?raw=true)

The **Star** will make Tux invincible for about 14 seconds, visualized by white sparks
surrounding him.

Tux Doll
--------

![](https://github.com/SuperTux/supertux/blob/master/data/images/powerups/1up/1up.png?raw=true)

The **Tux Doll** allows Tux to access the Bonus Island. When a certain percentage of Tux Dolls
are collected, A Bonus Island will unlock.

In previous versions of the game, Tux would instead gain 100 coins.

Before the life-system was discarded in Milestone 2, the Tux Doll granted one extra life.

---

Proposed Abilities
==================

Super-Butt-Jump
---------------

1.  Player moves Tux to a high position on the map
2.  Player jumps from the ledge
3.  Player presses 'down'
4.  Tux does some acrobatic movement to get into the 'butt-position'
5.  Tux then falls down back to the ground, butt first with increasing speed,
    due to the higher altitude he will change to Super-Butt-Jump-mode
6.  When smashing on the ground nearby enemies might be turned upside down,
    rendering them unmovable or killing them (might depend on the type of
    enemy and of the type of ground)
7.  It takes Tux a small amount of time to jump back onto his feet to get back to normal

Blowflyer
---------

![](images/Blowflyer.png)

The **Blowflyer** or **Balloon Tux** action would be a temporary limited action in
which Tux fills his body with air (helium?!) and is thus able to fly for a short time,
i.e. as long as he can go without breathing. The end of the flight should be announced
by Tux changing color and catching for air.

Perhaps there could be a hidden "pump" or balloon or in each level, which Tux could pump himself up with.

Flapping
--------

![](images/Flapping.png)

Once in the air, Tux should be allowed to flap with his wings. They are not enough to let him fly,
but should allow him to get some additional air-time (like a small double-jump).

- While not as a core ability, this could very well be turned into
  how Tux glides with the new air flower costume designs.
