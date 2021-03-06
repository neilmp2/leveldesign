# MP2 Game Design Document

## Video Explanation

[No Audio in Video -- Explanation]

First I show the first enemy, a mortar. It shoots out shells at random speeds in an arc. It will knock me back and do damage.

I actually decreased the amount of damage done because I died too many times while trying to do the recording...

Past the wall is a health pack and another mortar enemy that I can shoot.

Outside the hallway I deal with my rather persistent AI enemies that chase. The world is open so technically you could just skip to the end portal but that's not fun at all!

The black bullets do despawn after a couple seconds so the world is not being populated with actors constantly.

The gravity is quite low, so I can jump quite far. The C shaped objects are collectibles, they dont' restore health.

I also demonstrate the perils of low gravity plus knockback by being launched across the world. I then skip the segment I already did to the end building.

Nothing new here it's just tricky to avoid the enemies, especially if I dont' have damage reduction. (Diffuclty modes in final project!)

The final part is climbing the very slippery rock assets.

Death screen demo + run back to end.

Level complete!

## Design Decisions

Enemy Mortar: It doesn't target the player, instead it creates obstacles with the number of projectiles it creates that are mandatory to dodge.

AI: Just as described in the spec!

Health/Damage: I reduced the damage done by enemies but I am not sure about that decision. Having higher damage means I have to be very careful and cannot simply sprint though sections as I did for the demo.

Open world (ish): not really a typical platformer where you have to go through each section, but the game aesthetic and character really just fit a more open/less restricted playstyle

## Things I would change

- increase gravity, the gravity is very Lunar in character
- better weapon aim

- camera can be wonky, not sure how to fix that

## Sources Used

https://docs.unrealengine.com/4.26/en-US/InteractiveExperiences/UseTimers/  
https://www.youtube.com/watch?v=OB6ns9E3dUU&ab_channel=BigCatMatty  
https://docs.unrealengine.com/4.27/en-US/InteractiveExperiences/ArtificialIntelligence/BehaviorTrees/BehaviorTreeQuickStart/  
https://docs.unrealengine.com/4.26/en-US/InteractiveExperiences/UseTimers/
