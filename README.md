Server Version: **1.18.1**<br>
Supported Client Version: **1.13.x - 1.18.x**

## Server settings

**Mobspawn limit**
```
monsters: 40
animals: 10
water-animals: 5
water-ambient: 5
water-underground-creature: 5
ambient: 5
```
**Chunks**
[Controls the number of chunks that will be loaded around every player.]
```
view-distance: 8
simulation-distance: 5
mob-spawn-range: 4
```
**Entity-activation-range** 
[Controls the range in blocks that entities will become "activated" - entities outside of this range will tick at a reduced rate to prevent server lag.]
```
monsters: 24
animals: 16
villagers: 16
  - Lobotomized: true
    [Villager that are in 1x1 will stop functioning only focusing on trading, any farm tha tutilize that villager standing in 1x1 area need to be a 2x1 area for villager to walk]

![Images](/Images/IronGolemFarm.png)
RED: Air block, Movable Area for villager
BLUE: HostileMob
Black: Bed
```
**Despawn-ranges**
<br>
[SOFT: The number of blocks away from a player in which monsters will be randomly selected to be despawned.]
<br>
[HARD: The number of blocks away from a player in which monsters will be forcibly despawned.]
```
soft: 32
hard: 88
```
