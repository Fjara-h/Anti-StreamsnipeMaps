# StreamsniperMaps
 Semi-transparent stream overlays for Dota 2 minimap

# How-to:
Pick Marci
pause

## In-game chat:
```
-disablecreepspawn
-killcreeps all
-allvision
```

## In console:
```
sv_cheats true
dota_kill_buildings
dota_minimap_rune_size 0
dota_minimap_hero_size 0
dota_creeps_no_spawning true
dota_kill_creeps true
```

### Removing Fog of War (Optional):
```
dota_minimap_draw_fow false
```

## In-game chat:
Teleport to the enemy base and use ult to kill the remaining buildings

```
-wtf
-item blink
-item observer
-rapgod
-teleport
```

Focused in ally base, make sure to level the bot's ultimate:
```
-createhero marci enemy
-levelbots 30
-givebots item_rapier
-givebots item_rapier
-givebots item_rapier
-givebots item_rapier
```


## Warding:
Blink around and ward, enabling fog of war is recommended.

Screenshots:
Move camera to bottom left corner
Crop to outline
Each image is 70% opacity (30% opacity of an eraser)

### Small:
- Ancient: 14px centered
- Radiant fountain: 125px centered on the corner of the image
- Dire fountain: 140px centered on the corner of the image

#### Simple:
```
dota_minimap_simple_background true
dota_hud_extra_large_minimap 0
dota_minimap_draw_fow true
```
#### Complex:
```
dota_minimap_simple_background false
dota_hud_extra_large_minimap 0
dota_minimap_draw_fow true
```

### Large:
- Ancient: 15px centered
- Radiant fountain: 150px centered on the corner of the image
- Dire fountain: 165px centered on the corner of the image

#### Simple:
```
dota_minimap_simple_background true
dota_hud_extra_large_minimap 1
dota_minimap_draw_fow true
```
#### Complex:
```
dota_minimap_simple_background false
dota_hud_extra_large_minimap 1
dota_minimap_draw_fow true
```


### XLarge:
- Ancient: 24px centered
- Radiant fountain: 225px centered on the corner of the image
- Dire fountain: 255px centered on the corner of the image

#### Simple:
```
dota_minimap_simple_background true
dota_hud_extra_large_minimap 2
dota_minimap_draw_fow true
```
#### Complex:
```
dota_minimap_simple_background false
dota_hud_extra_large_minimap 2
dota_minimap_draw_fow true
```
