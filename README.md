# Knife Round
Simple SourceMod plugin that allows you to play an additional round before a match with knifes only. The round is being played after "Warmup" or at the start of the match if there is none. Winning team will choose starting side on this match via a menu.


# Installation
 - Compile knife_round.sp into knife_round.smx with an up-to-date sourcemod compiler
 - Put knife_round.smx into addons/sourcemod/plugins/
 - Put knife_round.phrases.txt into addons/sourcemod/translations/      
 - Restart the server


# Cvars
Add config overrides to cfg/sourcemod/knife_round.cfg
```
knifer_info 0-2 - Sets the messages display type (0 - no messages, 1 - chat, 2 - HUD)
knifer_roundtime 0.5-60.0 - Sets how long the knife round will last
knifer_votetime 5.0-20.0 - Sets how long the vote for team change will last
knifer_alltalk 0-1 - Sets if there will be alltalk enabled on knife round
knifer_unload "kento_rankme,rankme" - Unload these plugins while knife round is being played (separate plugins with commas)
knifer_free_armor - Make all players spawn with armor + helmet in knife round
```
