DoC Doc
=======

DoC Doc is a deck and game analysis tool for Might &amp; Magic: Duel of Champions.

This is the initial project for what will hopefully be a community-built client-server app that will ideally:

1. Use players' replay files to analyze game/deck
2. Store game data locally
3. Give per-turn probabilities for cards in decks
4. Generate random first hands & mulligans
5. Upload players' game data to server to maintain game history beyond replay file changes and reinstalls
6. Track card/deck usage across community via data on server

No firm decisions have been made as to how the whole thing will be architected or what language to use, so be sure to voice your thoughts in the [Issues](https://github.com/crawfordcomeaux/docdoc/issues) & be sure to give reasons for why your suggestions should be accepted.

How to Contribute
=================
- Help out with tasks below
- Comment on or fix the [Issues](https://github.com/crawfordcomeaux/docdoc/issues)
- Spread the word

Tasks
=====

- [ ] Decide language
- [ ] Decipher replay file codes
- [ ] Create databse of cards from cards*.xml
- [x] Write contribution instructions
- [ ] Commit XML-decoded replay file
- [ ] Provide directions for XML-decoding replay files

Replay Files
============

Duel of Champions creates a replay file after every match is played. These files can most easily be found by right-clicking on the shortcut for the game's launcher, clicking "Properties" and then clicking "Open File Location". The replay files are found in the GameData\Replay folder. If anyone wants to provide more specific instructions than this, feel free to commit a change to the README.

Instructions for viewing old games using replay files can be found [here](http://forums.ubi.com/showthread.php/761414-QUICK-GUIDE-watch-replays) and [here](http://forums.ubi.com/showthread.php/750659-Aza404Online-s-Youtube-Channel?p=8897731&viewfull=1#post8897731).

