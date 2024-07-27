Eastern Europe at War - ChangeLog
------------------------

## Version 3.2
 ### General
   * most cannons have 20% forest and fungus defense cap now
   * most cavalry units have 40% village defense cap now
 ### Units
   * Austrians (Habsburg Monarchy):
     * Battle Cannon: forest and fungus defense capped at 20%
     * Cannon: forest and fungus defense capped at 20%
     * Colonel Hussar: village defense capped at 40%
     * Culverin: forest and fungus defense capped at 20%
     * Dragoon: village defense capped at 40%
     * Elite Dragoon: village defense capped at 40%
     * Elite Hussar: village defense capped at 40%
     * Heavy Mortar: forest and fungus defense capped at 30%
     * Horse Artillery: village defense capped at 40%
     * Hussar: village defense capped at 40%
     * Mortar: forest and fungus defense capped at 30%
     * Veteran Horse Artillery: village defense capped at 40%
   * Cossacks (Cossack Hetmanate):
     * Big Tabor: shallow water defense from 10% to 20%
     * Fire Tabor: shallow water defense from 10% to 20%
     * Great Tabor: shallow water defense from 10% to 20%
   * Polish-Lithuanian Commonwealth:
     * Armoured: village defense capped at 40%
     * Armoured Companion: village defense capped at 40%
     * Cannon: forest and fungus defense capped at 20%
     * Infamis: fixed incorrect movement type; village defense capped at 40%
     * Lisovianus: fixed incorrect movement type; village defense capped at 40%
     * Small Cannon: forest and fungus defense capped at 20%
     * Zagonczyk: village defense capped at 50%
   * Prussians (Brandenburg-Prussia):
     * Colonial Marine: forest defense capped at 40%, fungus defense capped at 30%
     * Colonial Officer: fungus defense capped at 30%
     * Colonial Ranger: fungus defense capped at 30%
     * Colonial Veteran: fungus defense capped at 30%
     * Cuirassier: fungus defense capped at 30%
     * Dragoon: fungus defense capped at 30%
     * Engineer: forest and fungus defense capped at 30%
     * General: fungus defense capped at 30%
     * Grenadier: forest and fungus defense capped at 30%
     * Heavy Cannon: forest and fungus defense capped at 20%
     * Howitzer: forest and fungus defense capped at 20%
     * Leib Cuirassier: fungus defense capped at 30%
     * Leib Dragoon: fungus defense capped at 30%
     * Leib Grenadier: forest defense capped at 30%
     * Leib Guard: forest defense capped at 30%
     * Leib Guard Cuirassier: forest defense capped at 30%
     * Line Soldier: forest and fungus defense capped at 30%
     * Officer: forest defense capped at 40%, fungus defense capped at 30%
     * Recruit: forest and fungus defense capped at 30%
     * Sapper: forest and fungus defense capped at 30%
     * Siege Howitzer: forest and fungus defense capped at 20%
     * Veteran Lieb Grenardier: forest and fungus defense capped at 30%
     * Veteran Line Soldier: forest and fungus defense capped at 30%
   * Russians (Tsardom of Russia):
     * Don Ataman: village defense capped at 40%
     * Don Moloyec: village defense capped at 40%
     * Field Cannon: forest and fungus defense capped at 20%
     * Rynda: forest defense capped at 40%
     * Rynda Tsar Guard: forest defense capped at 40%
     * Small Cannon: forest and fungus defense capped at 20%
   * Swedes (Kingdom of Sweden):
     * Battle Cannon: forest and fungus defense capped at 20%
     * Cannon: forest and fungus defense capped at 20%
     * Hakkapeliitta: village defense capped at 40%
     * Recruit: forest and fungus defense capped at 40%
     * Royal Culverin: forest and fungus defense capped at 20%
     * Siege Cannon: forest and fungus defense capped at 20%
   * Tatars (Crimean Khanate):
     * Crimean Khan: village defense capped at 40%
     * Elite Horde Man: village defense capped at 40%
     * Elite Sharpshooter: village defense capped at 40%
     * Horde Man: village defense capped at 40%
     * Tatar: village defense capped at 40%
     * Tatar Bey: village defense capped at 40%
     * Tatar Bowman: village defense capped at 40%
     * Tatar Healer: village defense capped at 40%
     * Tatar Medic: village defense capped at 40%
     * Tatar Murza: village defense capped at 40%
     * Tatar Shooter: village defense capped at 40%
     * Dey: village defense capped at 40%   
   * Turks (Ottoman Empire):
     * Cannon: forest and fungus defense capped at 20%   
     * Heavy Cannon: forest and fungus defense capped at 20%   
 ### Traits
   * colonial (musthave): fixed incorrect defense bonus value
 ### Code
   * removed repeating defense values that overlaped with core values
 ### Translations
   * updated the Polish translation

## Version 3.1.1
 ### General
   * fixed incorrect forest defense for cavalry (it should no longer exceed 30-40% in most cases) - affected units: Croatian Companion, Croatian Rider, Elite Winged Hussar, Infamis, Lisovianus, Mercenary, Mounted Dragoon, Winged Hussar, Young Winged Hussar, Cuirassier, Dragoon, General, Leib Cuirassier, Leib Dragoon, Leib Guard Cuirassier, Leib Guard Dragoon, Hakkapeliitta
 ### Traits
   * colonial: fixed incorrect defense bonus value
 ### Translations
   * updated the Polish translation

## Version 3.1
 ### Abilities
   * the fortify ability cover bonus reduced from +20% to +10%
   * the fortify ability no longer grants +20% cover in a castle or keep
 ### Graphics
   * improved faction images
   * moved emblems to a separate folder
   * sprite cleanup & improvements
   * optimized images

## Version 3.0
 ### Structure
   * translated all folders and file names to English
   * renamed all unit files to match unit names
   * improved CREDITS.txt
   * added ART_LICENSE
 ### Code
   * translated all unit ids to English
   * translated all attack names to English
   * added eeaw_ prefix to all weapon specials and abilities
   * replaced 100 with {UNREACHABLE} in [movement_cost] for all units
   * fixed incorrect image path in Great_Chaika.cfg
   * project-wide code cleanup
 ### Descriptions
   * improved scenario descriptions
   * improved option descriptions
   * fixed typos
 ### Graphics
   * added longrange_attack.png
 ### Translations
   * updated the raw translation file
   * updated the Polish translation
 ### Other
   * began to keep a changelog