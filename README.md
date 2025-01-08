# SMG2-Restored-SMR.szs
This mod restores sounds from SMG which were dummied out in SMG2.<br>Every section below lists the Sound Labels you can/should put into your Galaxy's ``UseResource/sound_common.bcsv`` and the AW file you need to lookout for in the Dolphin File Log to check if the sounds were loaded properly.
## Future plans (v3.0?)
- Maybe add (instead of replacing) sounds for [Evanbowl's](https://github.com/Evanbowl) [Blue Coins](https://github.com/Lord-G-INC/Modular-PTD/tree/f528319c152605fd67db96d096f8b5ad8f13e427/PTD/BlueCoinSystem)
- Open for requests
## Standalone release (v2.0)
This version restored voice clips for the Luigi and Rosalina NPCs. Strangely Rosalina's Sound Labels were not changed in SMG2, however some of Luigi's dummied-out Sound Labels were renamed to ``SE_SV_DUMMY_XXX``, where XXX is the index of the sound inside the SUPPORTER_VOICE category.
### Luigi
| Sound Label              | AW file       |
|--------------------------|---------------|
| SE_SV_LUIGI_MARIO        | B117take_0.aw |
| SE_SV_LUIGI_SORRY        | B117take_0.aw |
| SE_SV_LUIGI_THANKS       | B117take_0.aw |
| SE_SV_LUIGI_TALK_HELP    | B117take_0.aw |
| SE_SV_LV_LUIGI_AFRAID    | B117take_0.aw |
| SE_SV_LUIGI_FALL         | B117take_0.aw |
| SE_SV_LUIGI_AFRAID_TOUCH | B117take_0.aw |
| SE_SV_LUIGI_ESCAPE       | B117take_0.aw |
### Rosalina
| Sound Label                     | AW file       |
|---------------------------------|---------------|
| SE_SV_ROSETTA_TALK_SURPRISE     | B114take_0.aw |
| SE_SV_ROSETTA_TALK_SMILE        | B114take_0.aw |
| SE_SV_ROSETTA_SWING             | B114take_0.aw |
| SE_SV_ROSETTA_TALK_WAITING      | B114take_0.aw |
| SE_SV_ROSETTA_TALK_WORRIED      | B114take_0.aw |
| SE_SV_ROSETTA_TALK_LETS_START   | B114take_0.aw |
| SE_SV_ROSETTA_TALK_SOMUCH_TODAY | B114take_0.aw |
| SE_SV_ROSETTA_TALK_THATS_ALL    | B114take_0.aw |
| SE_SV_ROSETTA_TALK_SO           | B114take_0.aw |
| SE_SV_ROSETTA_TALK_LOOK         | B114take_0.aw |
| SE_SV_ROSETTA_TALK_PLEASE       | B114take_0.aw |
| SE_SV_ROSETTA_TALK_FU           | B114take_0.aw |
| SE_SV_ROSETTA_TALK_TROUBLE      | B114take_0.aw |
| SE_SV_ROSETTA_TALK_SIGH         | B114take_0.aw |
| SE_SV_ROSETTA_TALK_QUESTION     | B114take_0.aw |
| SE_SV_ROSETTA_TALK_SMILE_EP_B   | B114take_0.aw |
## Unreleased update (v1.5)
For [Super Hackio's](https://github.com/SuperHackio) [GLE-V4 preview video](https://youtu.be/7QBAAAn7tD4?t=175), I made a small patch that allows the unused AW file with Starshine Beach's Koopa Shell drums to be loaded via UseResource. The Sound Label will not play the Koopa Shell drums, instead this is intended to be used with custom BMS files that make use of Koopa Shell drums and need the AW file loaded.
### Koopa Shell drums
| Sound Label    | AW file       |
|----------------|---------------|
| SE_PM_DUMMY_02 | B08mahit_0.aw |
## First release (v1.0)
Initially this mod was not planned to be developed any further than restoring Kingfin's and Bonefin's sounds for [Super Hackio's](https://github.com/SuperHackio) [Kingfin SMG2 port](https://github.com/SuperHackio/SMG2_SkeletalFishBossReturns).
### Kingfin
| Sound Label                   | AW file      |
|-------------------------------|--------------|
| SE_BM_LV_SKL_BOSS_SWIM_APPEAR | B83kawa_0.aw |
| SE_BM_LV_SKL_BOSS_SWIM_FAR    | B83kawa_0.aw |
| SE_BM_LV_SKL_BOSS_SWIM_NEAR   | B83kawa_0.aw |
| SE_BM_SKL_BOSS_MOUTH_OPEN     | B83kawa_0.aw |
| SE_BM_SKL_BOSS_MOUTH_CLOSE    | B83kawa_0.aw |
| SE_BM_SKL_BOSS_DAMAGE_S       | B83kawa_0.aw |
| SE_BM_SKL_BOSS_DAMAGE_L       | B83kawa_0.aw |
| SE_BM_SKL_BOSS_DAMAGE_LAST    | B83kawa_0.aw |
| SE_BM_LV_SKL_BOSS_SWIM_POW_UP | B83kawa_0.aw |
| SE_BM_LV_SKL_BOSS_SWIM_DIE    | B83kawa_0.aw |
| SE_BM_SKL_BOSS_BODY_SOLID     | B83kawa_0.aw |
| SE_BM_SKL_BOSS_EXPLODE        | B83kawa_0.aw |
| SE_BM_SKL_BOSS_EXPLODE_2      | B83kawa_0.aw |
### Bonefin
| Sound Label                    | AW file      |
|--------------------------------|--------------|
| SE_BM_SKL_GUARD_APPEAR         | B83kawa_0.aw |
| SE_BM_LV_SKL_GUARD_SWIM_NORMAL | B83kawa_0.aw |
| SE_BM_LV_SKL_GUARD_SWIM_ATTACK | B83kawa_0.aw |
| SE_BM_SKL_GUARD_ATTACK_START   | B83kawa_0.aw |
| SE_BM_SKL_GUARD_MOUTH          | B83kawa_0.aw |
| SE_BM_SKL_GUARD_EXPLODE        | B83kawa_0.aw |
| SE_BM_SKL_GUARD_COME_FRONT     | B83kawa_0.aw |
| SE_BM_LV_SKL_GUARD_ALARM       | B83kawa_0.aw |
