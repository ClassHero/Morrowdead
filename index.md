## documentation

### stats
- stamina (at first bad)
- food
- water
- infected
- temperature
- levels (tracking progress)
- experience
  - for upgrading weapon floats (random value from -0.020 to +0.050 is given per UPGRADE_TRY)
  
### storage
- player_inventory 6 slots
- light_backpack 4 slots
- op_backpack 4 slots
- chest 4 slots
  
### crates
Crates are defended by zombies. The more special the crate is, the more zombies surround it and the stronger they are.

**CRATE_TYPES**
- wooden_crate
- bronze_crate
  
### trader_post
This is the store. The trader doesn't always have everything. He has a secret stash too.
- selling items
- secret stash
- doesn't always have everything
- open from 6am-10pm

```
Store items

-- Medical --
Repair kit
Medkit
Bandage
Antibiotic

-- Special --
Name colorer
Name changer
Pet name changer

--Seeds--
pumpkin
potato

--Boosters--

armor,
mines,
clothes...

--Bullets--
Pumped up shells
Heavy piercer bullets
Super 7.62

```

### food
- eggs
- meat
- fish
- potatos
- berries
- frog meat
- water bottle
- mineral water

### tools
- fishing rod (fishing)
- axe
  - chopping wood for campfire
  - damaging zombies

### environment
- Short days (adjustable day/night duration)
- Day/Night Cycle
- Seasons
- Fog, Rain, Snow, Leaves
- Occasional hordes running around
- You die once, you are dead (except if you bought RESURRECTION_STONE)

### animals
- frog
- bird
- bunny
- deer
- wolves

### farms
- plant seeds anywhere for them to grow
- growth can be boosted with dirt humidifier

### pond
- can fill up water bottles
- can be used for fishing

**FISH_KINDS**
there has to be special fishes for fishing to be cool

### weapon float (quality)
```
- 1.000 - 0.000
- every 0.200 brown, gray, green, light_blue, pink
```

### integrate cheats
for testing purposes

**commands**

_NUMBEROF_, _NUMBER_ should be between 1 and 100.
_STATE_ should be ON or OFF.

- spawn _NUMBEROF_ fish
- give _NUMBER_ health
- stamina infinite _STATE_

