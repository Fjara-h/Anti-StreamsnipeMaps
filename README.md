# StreamsniperMaps
 Semi-transparent stream overlays for Dota 2 minimap

Patch 7.24:

Simple Backgrounds -

Small(244x244px): ![Simple - Small - 731](https://raw.githubusercontent.com/robuhde/StreamsniperMaps/master/731-Simple-Small-AntiStreamSnipeMap.png)

Large(280x280px): ![Simple - Large - 731](https://raw.githubusercontent.com/robuhde/StreamsniperMaps/master/731-Simple-Large-AntiStreamSnipeMap.png)

Extra large(420x420px): 
![Simple - Extra Large - 731](https://raw.githubusercontent.com/robuhde/StreamsniperMaps/master/731-Simple-XLarge-AntiStreamSnipeMap.png)


Complex Backgrounds -

Small(244x244px):![Complex - Small - 731](https://raw.githubusercontent.com/robuhde/StreamsniperMaps/master/731-Complex-Small-AntiStreamSnipeMap.png)

Large(280x280px):![Complex - Large - 731](https://raw.githubusercontent.com/robuhde/StreamsniperMaps/master/731-Complex-Large-AntiStreamSnipeMap.png)

Extra large(420x420px):![Complex - Extra Large - 731](https://raw.githubusercontent.com/robuhde/StreamsniperMaps/master/731-Complex-XLarge-AntiStreamSnipeMap.png)


How these are made (An incomplete guide):

Pick Marci
pause
-gold 99999
-wtf
-lvlup 30

buy ward + blink

dota_minimap_rune_size 0
dota_minimap_hero_size 0
-disablecreepspawn
(-killcreeps all)
-allvision

Ward everything
Screenshot in small, medium, large for complex and simple
dota_hud_extra_large_minimap 2

buy 4 rapiers and a salve, kill all dire towers
Screenshot in small, medium, large for complex and simple
dota_hud_extra_large_minimap 2

-createhero marci enemy
-levelbots 30
-givebots item_blink
-givebots item_heart
-givebots item_rapier
-givebots item_rapier
-givebots item_rapier
-givebots item_rapier

small: 14px circle, 95 radiant, 105 dire
normal: 15px circle, 115 radiant, 125 dire
large: 24px circle, 165

30% Opacity
