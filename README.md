All Postal 3 Achievements and how they work in Vanilla (unmodified) versions of Postal 3.  
Written by Kizoky

## Stallone
Events: non_melee_fired  
If event is fired even once, achievement fails  

## Eastwood
Events: non_pistol_fired  
If event is fired even once, achievement fails  

## Personal Jesus
Events: npc_death  
Achievement fails if ANY NPC dies  
If Faction is 'ZombieBoss' (12), achievement will not fail on NPC death  
Note: Never checks for killer, BUGGED!  

## Special Olympian  
Events: none  
Achievement is granted automatically on map end  

## PETA Chairman
Events: npc_death  
Achievement fails if ANY NPC dies with the 'Animals' (5) faction  
Note: Never checks for killer, BUGGED!  

## Daddy Never Loved Me
Events: npc_death  
Achievement fails if the following NPC dies with the following factions:  
- StGranny (4)
- SoccerMom (6)
- CuteGirl (7)
- Girl (11)

## I am The Law
Events: join_the_dark_forces  
If event is fired even once, achievement fails  

## Sucktastic
Events: shopvac_suckin  
Increments for each event fire  

### Kill With Weapon Achievements
Events: npc_death  
Conditions:  
- Player must be the killer
- Weapon must match
- Weapon flags must match (if there's any)

Champ Whisperer: 	  P3_WEAPON_DOG  

Cat Wrangler: 		  P3_WEAPON_CAT  

Entomologist: 		  P3_WEAPON_BEENEST  

Arsonist: 			    P3_WEAPON_MOLOTOV  

Danny Trejo: 		    P3_WEAPON_MACHETE  

Psycho Dundee: 		  P3_WEAPON_MACHETE  

Schwarzenegger: 	  P3_WEAPON_M60  

Wolverines R Ghey: 	P3_WEAPON_WOLVERINE  



## Curious Bastard (Deleted Achievement)
Events: npc_death  
Kill NPCs with all possible melee weapons  

## Dont Taze Me
Events: npc_unconscious  
Killer/Attacker must be the Player  
Weapon must be P3_WEAPON_TASER  

## Culture Warrior (Deleted Achievement)
Events: npc_death, npc_unconscious  
Killer/Attacker must be the Player  
Conditions:
- Manner must be SoccerMom (6) OR Faction must be Zealots (2)

## Real American
Events: npc_death, npc_unconscious  
Killer/Attacker must be the Player  
Manner must be JihadBeard (16)  

## Kavorikian
Events: npc_death  
Killer/Attacker must be the Player  
Manner must be StGranny (4)  
Note: NPCs with 'IsOld' attribute in Postal3Script will trigger this achievement

## Neurosurgeon
Events: npc_head_shot  
Increments for each event fire  

## Mega-Sadist
Events: npc_butched  
Killer/Attacker must be the Player  

## Toyota Recall
Events: entity_destroyed  
Increments for each event fire  
Type must be 1  

## Property Damage
Events: window_smashed  
Increments for each event fire  

## Fail Zombie
Events: player_respawn  
Increments for each event fire  

## Jack Thompson Was Right
Events: npc_death  
Killer/Attacker must be the Player  
Manner must be Bystander (23)  
Note: NPCs with 'flag_bystander' attribute in Postal3Script will trigger this achievement  

## Astronaut (Deleted Achievement)
Events: cat_launched  
Increments for each event fire  

## Bad Cop (Deleted Achievement)
Events: arrest_on_catnip  
Increments for each event fire  

## T J Hooker
Events: npc_arrest  
Increments for each event fire  

## Camelback
Events: plr_wee_start, plr_wee_stop  
Increments as long as Player keeps pissing  

## There Is No Spoon
Events: plr_catnip_start, plr_catnip_stop  
Increments as long as Catnip effect is on  

## Bipolar
Events: join_the_dark_forces, join_the_alliance  
Increments when the last path stored doesn't match chosen path  
Note: Quite buggy, last path isn't saved properly  

## Emo
Events: player_hurt  
Killer/Attacker must be the Player  
Increments when local player is the attacker  

### End Mission Achievements
Events: end_mission  
Conditions:  
- Name must match the map's name (i.e. 'pdb')

PDB  
CM  
GR(I) (Deleted)  
ML(I) (Deleted)  
AA2  
PWAC  
SRM  
ZHQA  
DLG  
BDK  
