## Battle royale gametype for Call of Duty 2 (2004)
Supported multiplayer patch: **1.3**
### Some setup instructions

- make the server to use ***fs_game*** not to override some players *main* folder files.
- use the libcod server extension.
  - i suggest [ibuddie's fork](https://github.com/ibuddieat/zk_libcod)
### Some TODO
- Prevent players from getting stuck in each other when exiting plane
  - MiscMod's [_newspawn function](https://github.com/cato-a/CoDaM_MiscMod/blob/4db1d420b87b766eb9bffb352a7d9c13eaa0c851/___CoDaM_MiscMod/codam/_mm_mmm.gsc#L379) might help
  - a solution can be to use `set x_contents "32"`
- Make the zone to move when shrinking
- Fill roofs and holes on the map
- Show the full zone on compass instead of just the center
- Create models and animations for skydiving
  - applying animations might require to add a `setAnim` GSC command to CoDExtended, like libcod
___
#### [Some videos](https://www.youtube.com/playlist?list=PLTiI1XPSd-uVS_saGvqfgk7hgguxHc1Y0)
___
#### Some credits
- *zh_frenzy* map: thanks to zilch
- The [Killtube](https://www.killtube.org/) community
- [cod.pm](https://cod.pm/)
  - Thanks to Cato
- [CoDExtended](https://github.com/xtnded/codextended)
- [vCoDMods](https://www.vcodmods.com/)
