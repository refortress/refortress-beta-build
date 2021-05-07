# [refortress](http://www.refortress.com)

refortress is a homage to Valve's Team Fortress Classic mod built from the ground up with the Half Life 1 SDK. License for Half-Life 1 SDK can be found in the LICENSE file in this repository.

## Differences to the original mod

I tried to make refortress play as closely to the original as I could, with a few quality-of-life improvements and a few experimental balance changes. There is also plenty that I didn't have time to implement. This was only a part-time hobby project, but it was a fun challenge to try to recreate the old classic. If there is any interest I'm happy to work on it further to improve its accuracy, implement missing features, or try something new and exciting.

Below is a very abridged list of some of the bigger differences you will notice:

- I haven't got round to implementing Pyro and Sniper classes.
- I haven't yet implemented a bunch of the map logic required for ADL or escape maps. They will partially work but things like round resets and timed scoring will be missing. Majority of CTF maps should work. I tested a lot of popular CTF maps.
- I haven't yet implemented caltrops, gas grenades or teleporters.
- I slimmed down the weapon loadouts a bit.
- I went a bit experimental on the Spy. Disguise-stealing backstabs, no longer sticky while feigned, quicker disguises, quieter weapons. Tried to make it play a little more covertly.
- I made hand-held concing completely predicted on the client - the timer, the player movement, everything.
- I made a few tweaks to bunnyhop speed limit, jumping, and added a speedometer.

So far I've only tested this with some very primitive bots. If anybody plays this with other people then I'd love to know what bugs/issues you find. I'll do my best to fix them.

## To install

Put the mod inside `Steam\steamapps\common\Half-Life\refortress` . You may need to restart Steam once or twice for it to pick it up in your game library. Team Fortress Classic must be installed. 

## Future plans?

I'm thinking about eventually open-sourcing this and/or maybe could even port it to Valve's Source Engine... (Maybe that's a little ambitious.)

## Contributing

- Feel free to cut me an issue on here for any bugs, suggestions, feedback, etc.
- You can also find me (Evrim) on the [The Catacombs Discord](https://discord.com/invite/WVXgAcZ).
