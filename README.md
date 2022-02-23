Server Version: **1.18.1**<br>
Supported Client Version: **1.18.x**

## Server settings

**Mobspawn limit**
```
monsters: 35
animals: 10
water-animals: 5
water-ambient: 10
water-underground-creature: 3
ambient: 7
```
**Chunks**
[Controls the number of chunks that will be loaded around every player.]
```
view-distance: 8
simulation-distance: 6
mob-spawn-range: 5
```
**Entity-activation-range** 
[Controls the range in blocks that entities will become "activated" - entities outside of this range will tick at a reduced rate to prevent server lag.]
```
monsters: 32
animals: 32
villagers: 16
  - Lobotomized: true
    [Villager that are in 1x1 will stop functioning only focusing on trading, any farm tha tutilize that villager standing in 1x1 area need to be a 2x1 area for villager to walk]

```
<br>
**Despawn-ranges**
<br>
[SOFT: The number of blocks away from a player in which monsters will be randomly selected to be despawned.]
<br>
[HARD: The number of blocks away from a player in which monsters will be forcibly despawned.]
```
soft: 32
hard: 80
```
**Farms/Mechanics**
<br>
**IronFarm**
```
Different from vanilla is that Villager need to switch between doing Villager stuff and being scared.
When modify/redesign the farm you need to take these into consideration. you have to ensure the villager can switch between doing normal things and being scared. not too fast, though. 
Here is an iron farm design i know works.
https://www.youtube.com/watch?v=ZMD4KlXdkqs
```
