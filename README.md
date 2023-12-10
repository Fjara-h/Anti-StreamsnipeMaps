# StreamsniperMaps
 Semi-transparent stream overlays for Dota 2 minimap

Each inner-most child folder of current has the following files:
* cover.png
* cover.psd
* unedited_minimap.png
* unedited_minimap.psd
* ward_map.png
* ward_map.psd

#TODO
Colorblind
Remove shrines
bright roshes
Adjust opacity instead of eraser

# How-to:
1. Pick Marci
2. pause

## 3. In-game chat:
```
-disablecreepspawn
-killcreeps all
-allvision
```

## 4. In console:
```
sv_cheats true
dota_kill_buildings
dota_minimap_rune_size 0
dota_minimap_hero_size 0
dota_creeps_no_spawning true
dota_kill_creeps true
```

### 4a. Removing Fog of War (Optional):
```
dota_minimap_draw_fow false
```

## 5. In-game chat:
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

## 6. Warding:
Blink around and ward, enabling fog of war is recommended.

Screenshots:
Wait for Daytime
Move camera to bottom left corner
pause
Take screenshots
host_timescale 100.000000
pause after 5 minutes and take dire rosh screenshot
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

# Observer ward icon

Use the simple minimap, kill all buildings except ancient, place a ward in the base away from the ancient on a flat-colored piece of minimap. Screen capture the small square of blue + ward. In GIMP, use Layer -> Transparency -> Color to Alpha and select the blue. Use the defaults and drag the threshold slightly above zero. Apply. Use the magic wand tool to select any remaining extranous pixels colored and delete them. Crop the image to content.