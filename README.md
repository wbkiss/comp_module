comp_module
===========

An ENL 3.2.0 based module system containing all the CoMP maps

Build instructions
==================
1) Download the latest module snapshot from https://github.com/wbkiss/comp_module/archive/master.zip

2) Unzip the file

3a) If you are using Windows, run build_module.bat. Note you will need Python 2.7 installed (see standard Warband Module System build instructions)

3b) If you are using *nix, run build.sh. You will also need Python 2.7 installed.

4) Once the build script has finished, a directory called "dist" will appear. It contains a complete Native and ENL compatible module.

5) Copy the contents of "dist" to the Modules/Native/ directory on your server. You don't have to have a module there prior to copying.

6) Optionally, you can copy the contents of "dist" to the Modules/Native/ directory on your client machine so that you can see the correct map names in the admin console.

Once again, the module is not intended for wide deployments as it changes often, but you're welcome to use it if that's what you want.

Maps
====
Map 1 - multi_scene_back_to_back
Display Name:  Back to Back
Author:        MadocComadrin
Terrain Code:  0x00000001300005004005fd84000011c60000285b00005cbe
Outer Terrain: outer_terrain_steppe
Flags:         sf_generate
Modes:         Battle, DM, TDM
Description:   

Map 2 - multi_scene_dreiecksdorf
Display Name:  Dreiecksdorf
Author:        MadocComadrin
Terrain Code:  0x00000000300000000005ad68000041ef00005ae800003c55
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 3 - multi_scene_forest_road
Display Name:  Forest Road
Author:        MadocComadrin
Terrain Code:  0x00000000b00005004004d53300007f6d00000fcf00004a0a
Outer Terrain: outer_terrain_plain
Flags:         sf_generate|sf_muddy_water
Modes:         Battle
Description:   

Map 4 - multi_scene_heisenburg
Display Name:  Heisenburg
Author:        HG
Terrain Code:  0x00000001300659630003c8f300003ca000006a8900003c89
Outer Terrain: sea_outer_terrain_2
Flags:         sf_generate
Modes:         Battle
Description:   

Map 5 - multi_scene_incursion
Display Name:  Incursion
Author:        Zaffa
Terrain Code:  0x000000013003d7e30005053f00003b4e0000146300006e84
Outer Terrain: outer_terrain_beach
Flags:         sf_generate
Modes:         Battle
Description:   

Map 6 - multi_scene_liberty
Display Name:  Liberty
Author:        Romans
Terrain Code:  0x00000000b0000500000350d600005d4600003c3100006cf6
Outer Terrain: outer_terrain_beach
Flags:         sf_generate
Modes:         Battle
Description:   

Map 7 - multi_scene_new_nord_town
Display Name:  New Nord Town
Author:        MadocComadrin
Terrain Code:  0x0000000030015f2b000350d4000011a4000017ee000054af
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 8 - multi_scene_new_port_assault
Display Name:  New Port Assault
Author:        Erminas
Terrain Code:  0x000000013003d7e30005053f00003b4e0000146300006e84
Outer Terrain: outer_terrain_beach
Flags:         sf_generate
Modes:         Battle
Description:   

Map 9 - multi_scene_open_plain
Display Name:  Open Plains
Author:        KissMyAxe
Terrain Code:  0x0000000130000000000641900000bf4a00001d670000d869
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 10 - multi_scene_quagmire
Display Name:  Quagmire
Author:        MadocComadrin
Terrain Code:  0x00000000b00005000003d8f200007f6d00000fcf00004a0a
Outer Terrain: outer_terrain_plain
Flags:         sf_generate|sf_muddy_water
Modes:         Battle
Description:   

Map 11 - multi_scene_rock_port
Display Name:  Rock Port
Author:        Romans
Terrain Code:  0x0000000230024e0a800435130000794a0000305500001978
Outer Terrain: outer_terrain_beach
Flags:         sf_generate
Modes:         Battle
Description:   

Map 12 - multi_scene_ruins_rebuilt
Display Name:  Ruins Rebuilt
Author:        Erminas
Terrain Code:  0x00000001300389800003a4ea000058340000637a0000399b
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 13 - multi_scene_solace
Display Name:  Solace
Author:        Romans
Terrain Code:  0x00000001300389800003a4ea000058340000637a0000399b
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 14 - multi_scene_swadian_town
Display Name:  Swadian Town
Author:        MadocComadrin
Terrain Code:  0x00000001300000000003c4f0000041ef00005ae800003c55
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 15 - multi_scene_the_farm
Display Name:  The Farm
Author:        Romans
Terrain Code:  0x000000033000053d000735cd00001e2100004c8e000039a9
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 16 - multi_scene_verloren
Display Name:  Verloren
Author:        Lord Rich
Terrain Code:  0x00000001300389800003a4ea000058340000637a0000399b
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Battle
Description:   

Map 17 - multi_scene_glitteron_temple_summit
Display Name:  Glitterond Temple Summit
Author:        TGD_Direct
Terrain Code:  0x000000005007b2630003b8f7000055f70000353700004892
Outer Terrain: sea_outer_terrain_2
Flags:         sf_generate
Modes:         Duel
Description:   Featuring the Shrine of Ida and the Temple of Glitterond. Inspired by the ancient roman and greek design. Duel high above the plateau of the mountain top or one the stair cases ascending the summit but watch your footing there are no reprieves for the unwary.  Separate 1v1 arena with invs. barrier in the summit garden. Many pilgramage to give offering the goddess Idya, few know that the Temple Grounds once housed a mythical relic of war. Features horse spawns & weapon with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

Map 18 - multi_scene_nord_town
Display Name:  Nord Town
Author:        TGD_Direct
Terrain Code:  0x0000000030015f2b000350d4000011a4000017ee000054af
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Duel
Description:   Nord town in the time of the Skald, the sea raiders have returned rich with plunder and the feast is prepared in their honour. An old flying disc is laid to rest on the upper floors of the main hold, duel in the open town center or 1v1 in a portculis courtyard.  Suitable for duel or deathmatch. Features Weapon spawns with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

Map 19 - multi_scene_pokonji_dol_island
Display Name:  Pokonji Dol Island
Author:        Bloody Mary
Terrain Code:  0x0000000033a7946000028ca300007f4a0000479400161992
Outer Terrain: sea_outer_terrain_2
Flags:         sf_generate
Modes:         Duel
Description:   A watery island, known as Pokonji Dol. Features separate duel enclosure. Features weapon spawns with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus

Map 20 - multi_scene_ramses_realm
Display Name:  Ramses Realm
Author:        Spec
Terrain Code:  0x000000075006c5000002dd560000088f000020c200004231
Outer Terrain: outer_terrain_desert
Flags:         sf_generate
Modes:         Duel
Description:   Ramses the first, legends say he descended from the sky. An old flying disc is laid on the pyramid summit. Duel in the sands or under the shade of the temple ruins. Features weapon spawns with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

Map 21 - multi_scene_skada_arena
Display Name:  Skada Arena
Author:        TGD_Direct
Terrain Code:  0x00000002200005000005f57b00005885000046bd00006d9c
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Duel
Description:   Arena map based on open duels, separate tournament area for jousts and archery. For 1v1 duels, a central area with seating is avaliable with invisible barriers and a tournament armoury. Features weapon spawns with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

Map 22 - multi_scene_skodja_clearing
Display Name:  Skodja Clearing
Author:        TGD_Direct
Terrain Code:  0x00000000b00037630002308c00000c9400005d4c00000f3a
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Duel
Description:   Skyrim inspired clearing based on forest hideout, Central clearing area for open duels, with many hidden places to explore. A skull and sword is set overlooking the grounds, under its watchful gaze scores of aspirants have become warriors, legends surrounding the relics tell of an origin belonging to a ancient swordsmen whose feats have since passed into myth. It now keeps watch over clearing, silent and immortal. Features weapon spawns with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

Map 23 - multi_scene_the_cage
Display Name:  The Cage
Author:        MadocComadrin
Terrain Code:  0x00000002200005000005f57b00005885000046bd00006d9c
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Duel, TDM, DM
Description:   

Map 24 - multi_scene_the_hall
Display Name:  The Hall
Author:        Snake
Terrain Code:  0x00000000500005000004210b0000511500003d400000093c
Outer Terrain: outer_terrain_desert
Flags:         sf_generate
Modes:         Duel
Description:   The Hall of an ancient king, double level enclosed arena, teleport to outer courtyards and arming chambers or 1v1 your opponent in a private duel area within. Features weapon spawns with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

Map 25 - multi_scene_tower_on_the_hill
Display Name:  Tower on the Hill
Author:        Spec
Terrain Code:  0x00000001300389800003a4ea000058340000637a0000399b
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Duel
Description:   The Tower on the hill. Open area duelling field, teleport doors to the tower and separate 1v1 duel arena on the hill top. Features weapon spawns with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

Map 26 - multi_scene_verovicium_army_camp
Display Name:  Verovicium Army Camp
Author:        TGD_Direct
Terrain Code:  0x00000001300005000004ed39000058340000637a0000399b
Outer Terrain: outer_terrain_plain
Flags:         sf_generate
Modes:         Duel
Description:   A enclosed army camp with accessible gates and porticulus gate entry. Central army pavillion seating & entertainment area incl. 3 tier benches for group portraiture. Main centre dueling ground and separate enclosures for 1v1 combatants. Features horse spawns & weapon with NeoGk Mod/ Item Refil and First-to-Seven Anvil function with The_Ludus Compatible with The_Ludus/Neo-GK mod

