# cFixes - Community fixes to HBS BATTLETECH
Bugs fixed as reported here:
https://forum.paradoxplaza.com/forum/index.php?threads/simple-json-typo-fixes-post-1-4-0.1126334/

These files are the result of the combined work of several community modders, namely:

- Amechwarrior, Hawaii, bug tracing and code review.
- Dr. Banzai, Germany, bug fixing and configuration management.
- scJazz, US East Coast, bug fixes and code review.
- JustinKaseToo, US East Coast (living on West Coast time according to his wife), bug and formatting fixes.
- Sheepy, bug fixes and code review.

Credits:

Thanks to the community at large for helping bring these bugs to HBS's attention!

This mod is intended for free use and re-use.

### Instructions:
    Remove older editions of cFixes.
    Copy cFixes folder in to Mods folder created for ModTek.
    
### ModTek/BTML
This mod needs ModTek to work:

https://github.com/BattletechModders/ModTek/releases

Thanks to mpstark and the entire ModTek team for making this mod possible!


## List of Fixes

### StreamingAssets/data/chassis/
    chassisdef_banshee_BNC-3S.json - fixed costs
    chassisdef_blackjack_BJ-1DB.json - fixed costs
    chassisdef_blackknight_BL-6-KNT.json - fixed variant name to BK-7-KNT
    chassisdef_blackknight_BL-6b-KNT.json - fixed reference to BK-7-KNT
    chassisdef_cicada_CDA-2A.json - fixed costs
    chassisdef_crab_CRB-27.json - fixed costs
    chassisdef_cyclops_CP-10-Q.json - fixed costs
    chassisdef_hatchetman_HCT-3F.json - fixed costs
    chassisdef_hatchetman_HCT-3X.json - fixed costs
    chassisdef_highlander_HGN-732b.json - fixed "732B" to "732b"
    chassisdef_hunchback_HBK-4G.json - melee DMG to 75 from 80
    chassisdef_hunchback_HBK-4P.json - melee DMG to 75 from 80
    chassisdef_javelin_JVN-10F.json - fixed costs
    chassisdef_javelin_JVN-10N.json - fixed costs
    chassisdef_raven_RVN-1X.json - fixed costs
    chassisdef_urbanmech_UM-R60L.json - fixed costs
    chassisdef_urbanmech_UM-R90.json - fixed costs
    chassisdef_vindicator_VND-1AA.json - fixed costs

### StreamingAssets/data/contracts/
All Escort and Capture Base contracts have had the word "Dropship" replaced with "DropShip" as used in the BT writers guide.

    AttackDefend_Reconquest.json - typos (Goddness and DropShip)
    AttackDefend_Retaliation.json - enabled def. turrets as dialogue text implies, typos (Goddness and DropShip)
    FireMission_DataLiberation.json - typos (Reinforments and DropShip)
    FireMission_DataLiberation_Hard.json - typos (Reinforments and DropShip)
    FireMission_FireForEffect.json - typos, too many to list here
    FireMission_Fireworks.json - "WarShip" changed to "Pocket WarShip" as no true WarShips should be available.
    lastChance_a1_3wayBattle.json - Removed chance for turrets to appear
    SimpleBattle_RaidingParty.json - DropShip foramtting
    SimpleBattle_RaidingParty_Hard.json - DropShip foramtting
    succession_1_assassinate - typos (commision and intitial)
    succession_a1_assassinate.json - typos (commision and intitial)
    ThreeWayBattle_TestDrive.json - Exclude Cap.Con from being employer stealing from Cap.Con

### StreamingAssets/data/descriptions/Lore/ - CHECKED GOOD FOR 1.9.1
    LoreGreatHouses.json - ordered Houses "Around the Sphere"
    LoreSuccessorState.json - ordered Houses "Around the Sphere"

### StreamingAssets/data/events/
    event_mw_dubiousIntentions.json - "You" replaced with "You're" in results error
    event_mw_leadershipMoment.json - added contextual words to fix "they rises" error
    event_mw_nobleBonds.json - Fixed the gender reference instead of defaulting to their
    event_mw_smugglingOnPurpose.json - Missing space between "report[s]that" in option3 result
    event_mw_spotlight_dekker.json - Typo "recupterating", even dekker's event is injured...
    event_mw_triage.json - missing commas
    
### StreamingAssets/data/factions/ - CHECKED GOOD FOR 1.9.1
    faction_KellHounds.json - Demonym fixed missing space between "KellHounds"

### StreamingAssets/data/flashpoints/
    fp_uw1.json - Spawn weight 200 from 10 to match "Joint Venture"

### StreamingAssets/data/hardpoints/
    hardpointdatadef_trebuchet.json - fixed RA blank slot in hardpoint 2 (slot 1)
    
### StreamingAssets/data/heatsinks/
    Gear_HeatSink_Generic_Bulk-Bank.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Improved-Bank.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Standard-Bank.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Thermal-Exchanger-I.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Thermal-Exchanger-II.json - fixed [AMT] value in StatusEffect Description Details
    Gear_HeatSink_Generic_Thermal-Exchanger-III.json - fixed [AMT] value in StatusEffect Description Details

### StreamingAssets/data/mech/
    mechdef_banshee_BNC-3S.json - fixed costs
    mechdef_blackjack_BJ-1DB.json - fixed costs
    mechdef_blackknight_BL-6-KNT.json - fixed variant name to BK-7-KNT
    mechdef_blackknight_BL-6b-KNT.json - fixed reference to BK-7-KNT and 6b, moved DHS, fixed costs
    mechdef_cicada_CDA-2A.json - fixed costs
    mechdef_crab_CRB-27.json - given Role - Brawler and Lance - Tank tags, fixed costs
    mechdef_cyclops_CP-10-Q.json - given Role - Sniper and Lance - Support tags, removed duplicate IDF tag, fixed costs
    mechdef_cyclops_CP-10-Z.json - given Role - Sniper and Lance - Support tags, removed duplicate IDF tag, fixed costs
    mechdef_griffin_GRF-4N.json - fixed JJ from Leg to Torso, moved DHS from illegal Leg slots to torsos to match "Greed"
    mechdef_griffin_GRF-4N_fp_greed.json - fixed JJ from Leg to Torso
    mechdef_hatchetman_HCT-3F.json - given Lance - Assassin tag, removed duplicate jumpOK tag, fixed costs
    mechdef_hatchetman_HCT-3X.json - given Lance - Assassin tag, removed duplicate jumpOK tag, changed faction tag, fixed costs
    mechdef_highlander_HGN-732b.json - Adjusted Torso Front Armor to match Record Sheets, 1b from 1B typos
    mechdef_highlander_HGN-733.json - Adjusted Center Torso Front Armor to match Record Sheets, allocated "spare" armor point to CTR
    mechdef_highlander_HGN-733P.json - adjusted Torso Front Armor and HS+ammo locations to match Record Sheets
    mechdef_javlin_JVN-10F.json - given Lance - Assassin/Vanguard tag, removed duplicate jumpOK tag, fixed costs
    mechdef_javlin_JVN-10N.json - given Lance - Assassin/Vanguard tag, removed duplicate jumpOK tag, fixed costs
    mechdef_raven_RVN-1X.json - fixed costs
    mechdef_urbanmech_UM-R60L.json - given Lance - Tank tag,
    
### StreamingAssets/data/milestoneSets/    
    ms_fp_doubleAgent.json - fixed Taurian rep (was Steiner) in reward ms for all branches
    
### StreamingAssets/data/movement/
    movedef_PACKRAT.json - max walk 210 from 200
    movedef_GALLANT.json - slowed down Gallant to TT speeds

### StreamingAssets/data/pilot/ - Current WIP manual check of every modded file vs 1.9.1, cleared d3-d7 pilots, resume on d8
All pilot files have been refactored to stock passive traits, this is over 90+ files and summerized here for brevity.  Any missing passive traits have been added to conform to the standard progressions.  Story pilots with more than the normal amount of abilities have been retained, but their passive traits have been brought up to standard.  Turret "pilots" have not been touched.

### StreamingAssets/data/regions/ - CHECKED GOOD FOR 1.9.1
    regionDef_Positive.json - typo (Positve)

### StreamingAssets/data/simGameConstants/ - It's complicated, come back to this later
    SimGameConstants.json - max contract fixes for 5+ skull contracts, various extra commas, missing commas

### StreamingAssets/data/starsystem/ - CHECKED GOOD FOR 1.9.1
    starsystemdef_Camadeirre.json - fixed typo: "Camadeirre" change to "Camadeierre"
    
### StreamingAssets/data/turrets/ - CHECKED GOOD FOR 1.9.1
    turretdef_Standard_Laser.json - renamed "Standard Laser Turret" from "Light Standard Turret"

### StreamingAssets/data/vehicle/ - CHECKED GOOD FOR 1.9.1
    vehicledef_BULLDOG.json - added Front MG and ammo
    vehicledef_DEMOLISHER.json - added missing 4th ton of AC/20 ammo
    vehicledef_GALLANT.json - fixed armor to TT values, LRM hardpoint slot adjustment
    vehicledef_MOBILEHQ_ARMORED.json - fixed armor to match TT values
    vehicledef_SCORPION.json - moved MG from Turret to Front
    vehicledef_STRIKER.json - fixed value: Turret Armor 120 changed to 110
    vehicledef_SWIFTWIND_ARMORED.json - fixed tonnage and armor to match possible TT config

### StreamingAssets/data/vehicleChassis/ - CHECKED GOOD FOR 1.9.1
    vehiclechassisdef_GALLANT.json - fixed weight class to Heavy
    vehiclechassisdef_MANTICORE.json - fixed armor and internals
    vehiclechassisdef_SCORPION - moved AP hardpoint from Turret to Front
    vehiclechassisdef_STRIKER.json - fixed armor and internals
    vehiclechassisdef_SWIFTWIND.json - fixed armor and internals
    vehiclechassisdef_SWIFTWIND_ARMORED.json - fixed Tonnage and armor and internals

### StreamingAssets/data/weapon/ - CHECKED GOOD FOR 1.9.1
    Weapon_Gauss_Gauss_1-M7.json - tag fixes
    Weapon_Gauss_Gauss_2-M9.json - tag fixes
    Weapon_Laser_LargeLaserER_1-Blankenburg25.json - tag fixes
    Weapon_Laser_LargeLaserER_2-BlazeFire.json - tag fixes
    Weapon_Laser_LargeLaserPulse_1-Thunderbolt12.json - tag fixes
    Weapon_Laser_LargeLaserPulse_2-Exostar.json - tag fixes
    Weapon_Laser_MediumLaserER_1-MagnaVI.json - tag fixes
    Weapon_Laser_MediumLaserER_2-BrightBloom.json - tag fixes
    Weapon_Laser_MediumLaserPulse_1-RakerIV.json - tag fixes
    Weapon_Laser_MediumLaserPulse_2-Magna400P.json - tag fixes
    Weapon_Laser_SmallLaserER_1-Diverse_Optics.json - tag fixes
    Weapon_Laser_SmallLaserER_2-BlazeFire.json - tag fixes
    Weapon_Laser_SmallLaserPulse_1-Maxell.json - tag fixes
    Weapon_Laser_SmallLaserPulse_2-Magna200P.json - tag fixes
    Weapon_PPC_PPCER_1-MagnaFirestar.json - tag fixes
    Weapon_PPC_PPCER_2-TiegartMagnum.json - tag fixes
