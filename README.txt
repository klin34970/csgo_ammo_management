I - Description

Everytime I had a Valve update"items_game.txt"was reset.
So I did this plugin for my community Zombie4ever.eu and Zombie Escape/Riot servers.
Allow you to manage weapon ammo instead of using"items_game.txt"

II - Cvars

drapi_ammo_338mag_max "30" - AWP
drapi_ammo_357sig_max "52" - HPK2000
drapi_ammo_357sig_min_max "12" - CZ75
drapi_ammo_357sig_p250_max "26" - P250
drapi_ammo_357sig_small_max "24" - USP-S
drapi_ammo_45acp_max "100" - FIVESEVEN
drapi_ammo_50AE_max "35" - DEAGLE
drapi_ammo_556mm_box_max "200" - M249, NEGEV
drapi_ammo_556mm_max "90" - M4A1, AK47, FAMAS, GALILAR
drapi_ammo_556mm_small_max "40" - M4A1-S
drapi_ammo_57mm_max "100" - P90, UMP45, MAC10
drapi_ammo_762mm_max "90" - SSG08, AUG, SG556, G3SG1, SCAR20
drapi_ammo_9mm_max "120" - ELITE, TEC9, MP7, MP9, GLOCK, BIZON
drapi_ammo_buckshot_max "32" - MAG7, NOVA, SAWEDOFF, XM1014

This are default ammo. Don't put less than this values in your config"/csgo/cfg/sourcemod/drapi/drapi_ammo.cfg".

III - Bugs

FIXED-For no reason, if you reach 0 ammo you will get in plus default ammo of weapon.
So what I did for example, AK47 Weapon ammo = drapi_ammo_556mm_max - default ammo.

VI - Credits

SMLIB for some useful functions

VII - Changelogs

V1.3.1
-Fixed ump45, mac10 -> ammo_45acp_max, fiveseven -> ammo_57mm_max, ak47 -> ammo_762mm_max
V1.3.0
Use m_iItemDefinitionIndex to simplify.
V1.2.0
-Added M4A1.
-No bug anymore when reach 0. Ammo are set correctly.
V1.1.2
-Detect weapons silencer.
V1.1.1
-Correct ammo when round start.
V1.1.0
-Tried on differents SM version works.