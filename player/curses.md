# Nexion - Curses
*This document adds a new kind of spells to the D&D 5e framework. Any content in this document can be used in other campaigns as well.*  
***Warning: this mechanic is in-development and might be changed or removed altogether.***

## Table of Contents
 - [Table of Contents](./curses.md#table-of-contents)
 - [Curses Mechanic](./curses.md#curses-mechanic)
   - [Class Requirements](./curses.md#class-requirements)
     - [Becoming a Curser](./curses.md#becoming-a-curser)
   - [Curse Slots](./curses.md#curse-slots)
   - [Five Stages](./curses.md#five-stages)
     - [Prepared](./curses.md#prepared)
     - [Cast](./curses.md#cast)
       - [Wild Ricochet](./curses.md#wild-ricochet)
     - [Active](./curses.md#active)
     - [Karma](./curses.md#karma)
     - [Finished](./curses.md#finished)
 - [Nexion Curses](./curses.md#nexion-curses)
   - [Curse of Crawling](./curses.md#curse-of-crawling)
   - [Curse of Lithomancy](./curses.md#curse-of-lithomancy)

## Curses Mechanic
Curses provide you with the option to put a detrimental effect on an opponent. Each curse has its own trigger, which causes an effect. This effect can be detrimental to the opponent, or beneficial to you. However, they can be unpredictable. Curses that kill people cause karmic justice on the curser.

### Class Requirements
To be a curser, you need to be a caster already: without spell slots, you won't be able to cast your own curses.

#### Becoming a Curser
At any level where you would gain one or more traits, you can instead choose to replace any one of them by becoming a Curser. (You can choose to forgo Ability Score Increases in favor of becoming a Curser.)

**Example:** *as a level 3 Paladin (having just become level 3), I can choose to replace either* Divine Health *or* Sacred Oath *and become a Curser in its place.*

### Curse Slots
While resting, you can choose to spend one hour preparing a curse. If you do, select one of your spell slots (of level 1 or greater). That spell slot can't be used but instead "holds" a prepared curse. Also select a curse for the spell slot to hold. This still counts as light activity. This converts your spell slot into a curse slot (you can't regain the spell slot until the curse finishes).

**Example:** *as a level 9 Paladin, I have access to 4 first level spell slots, 3 second level ones and 2 third level ones. This means that during a short rest, I can prepare* [Curse of Crawling](./curses.md#curse-of-crawling) *by "spending" a first, second or third level spell slot. Say I choose a second-level spell slot, then that means I still have 4 level one slots, 2 level two ones and 2 level three slots left to cast "normal" spells. After another hour, I can start preparing a second curse,* [Curse of Lithomancy](./curses.md#curse-of-lithomancy) *for example as a level 3 spell. Afterwards, I'll have the following spell slots left: 4x level 1, 2x level 2, 1x level 3.*

### Five Stages
A Curse can be in any of the five following stages: prepared, cast, active, karma and finished.

#### Prepared
The curse has been slotted into a spell slot and has been prepared. When the curse is in this stage, it can be cast by using one action. Casting requires a target.

**Example:** *(continuing on the previous example) with the* [Curse of Crawling](./curses.md#curse-of-crawling) *prepared, I can cast it on, say, an enemy Ogre. This takes one action and, supposing I haven't cast anything before, I have the* [Curse of Lithomancy](./curses.md#curse-of-lithomancy) *left prepared, as well as another 3 level 1 spell slots, 2 level 2 and 1 level 3 spell slot.*

#### Cast
When the curse is cast, it isn't yet in effect. At this stage, the target has to make a Spell Save. The Save DC is equal to `the curse's Base DC + your proficiency bonus + your spellcasting ability modifier`. If the target fails the save, it is afflicted by the curse, and the curse is active.  
However, if the target succeeds the save, the magic might be deflected onto someone else. Roll 1d20:  

 Result | Effect
 --- | ---
 1 - 7 | The magic is diffused. The curse is finished.
 8 - 19 | The magic ricochets away. See [Wild Ricochet](./curses.md#wild-ricochet).
 20 | The magic bounces back onto the the same creature. Repeat the [cast](./curses.md#cast) stage next turn.

##### Wild Ricochet
When the magic ricochets away from the target, it triggers two effects:  
 1. At first, a random Wild Magic Surge (![phb]) happens at the target's location.  
 1. Secondly, a random other creature is selected. The curse is "re-cast" targeting the other creature the next turn; it's still in the [cast](./curses.md#cast) stage.

#### Active
During this stage, the curse is in effect. Whenever the trigger is satisfied, the curse's effect is applied. This last for either the duration (this can be indeterminate) or until the creature afflicted died. If the creature dies before the curse "expires", the curse moves on to the [karma](./curses.md#karma) stage. If the curse ends because of the duration, it moves on to the finished stage. Once the curse ends (either way), the caster finally can use the spell slot again (the spell slot can be used immediately after the curse ends).

#### Karma
Karmic justice is applied when the cursed creature dies while the curse is active. When this happens, the original caster has to make a Spell Save against the (possibly changed) DC. The DC is recalculated as `Base DC + current proficiency bonus + current ability modifier`. If the caster fails this Save, they are afflicted by the curse for the next 1d6 hours. Otherwise, the spell ends and goes into the finished stage.

## Nexion Curses
Below are some curses you can use. Each curse can be prepared using a spell slot of level one or higher.

### Curse of Crawling

 Curse of Crawling | <i></i>
 --- | ---
 Base DC | 6
 Trigger | When the afflicted creature hits another creature with a melee attack.
 Duration | 10 days.
 At higher levels | For each level beyond the first, the duration is extended by 1d4 days.
 Base Effect | 1d4 Crawling Claws (![mm]) are summoned as near as possible to the creature. They are hostile towards the afflicted creature.
 At higher levels | For each level beyond the first, another 1d4 Crawling Claws are summoned. When cast as level 10 or higher, double the amount of Crawling Claws summoned.

### Curse of Lithomancy

 Curse of Lithomancy | <i></i>
 --- | ---
 Base DC | 8
 Trigger | When the afflicted creature touches an nonmagical object that's not made of stone.
 Duration | 40 hours.
 At higher levels | For each level beyond the first, the duration is extended by 1d8 hours.
 Base Effect | There is a 20% chance that the object turns to stone. 
 At higher levels | For each level beyond the first, there is an additional 10% chance that the object turns to stone.

[//]: # (links)
[phb]: https://img.shields.io/badge/resource-PHb-orange
[mm]: https://img.shields.io/badge/resource-MM-blue
[volo]: https://img.shields.io/badge/resource-Volo-lightgrey
[dmg]: https://img.shields.io/badge/resource-DMG-purple
