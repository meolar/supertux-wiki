> This file is auto-generated from the [SuperTux source code](https://github.com/SuperTux/supertux/tree/master/src), using the template [ScriptingPage.md](https://github.com/SuperTux/wiki/tree/master/templates/ScriptingPage.md).

Summary
-------

A `DartTrap` that was given a name can be controlled by scripts. It shoots darts at regular intervals. 

Instances
--------

A `DartTrap` is instantiated by placing a definition inside a level. It can then be accessed by its name from a script or via `sector.name` from the console. 

Inheritance
--------

This class inherits functions and variables from the following base classes:
* StickyBadguy
* [BadGuy](https://github.com/SuperTux/supertux/wiki/ScriptingBadGuy)
* [MovingSprite](https://github.com/SuperTux/supertux/wiki/ScriptingMovingSprite)
* [MovingObject](https://github.com/SuperTux/supertux/wiki/ScriptingMovingObject)
* [GameObject](https://github.com/SuperTux/supertux/wiki/ScriptingGameObject)
* Portable
* GameObjectComponent


Methods
-------

Method | Explanation
-------|-------
`Delay in seconds get_fire_delay()` | Gets the delay between consecutive dart firings 
`void set_fire_delay( fire_delay)` | Sets the delay between consecutive dart firings <br /><br /> `fire_delay` - Delay in seconds 
`Ammunition of the darttrap, -1 for infinite ammunition. get_ammo()` | Gets the amount of ammunition the darttrap has. 
`void set_ammo( ammo)` | Sets the amount of ammunition the darttrap has. <br /><br /> `ammo` - Ammunition the darttrap is supposed to have, -1 for infinite ammunition. 
`void enable()` | Enables the DartTrap. 
`void disable()` | Disables the DartTrap. 


Variables
---------

None.

Constants
---------

None.
