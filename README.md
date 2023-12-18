## Gametype under development, currently almost playable

### Requirements to run the tests

- make the server to use ***fs_game*** not to override some players *main* folder files.
- put ***assets.pk3*** in the *fs_game* folder, this file must be downloaded by the client.
- setup ***br.gsc*** in a *pk3* file like a stock gametype and put it in the *fs_game* folder.
  - give the priority to this pk3 over the assets one, because the assets pk3 contains a file named *br.gsc* too
- use the *zh_frenzy* map version of this repo.
- use the CoDExtended server extension.
  - i suggest [my fork](https://github.com/raphael12333/codextended-server) e.g. to allow non-living players to talk without showing messages to alive players
___
### Some TODO
- Make the zone to move semi-randomly when shrinking
- Fill roofs and holes on the map
- Show the full zone on compass instead of just the center
- Create models and animations for skydiving
  - applying animations might require to add a `setAnim` GSC command to CoDExtended, like libcod
___
#### [Test videos](https://www.youtube.com/playlist?list=PLTiI1XPSd-uVS_saGvqfgk7hgguxHc1Y0)
___
#### Some credits
- [www.killtube.org](https://www.killtube.org/)
- [www.cod.pm](https://cod.pm/)
- [www.vcodmods.com](https://www.vcodmods.com/)
