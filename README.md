This started as just a web app that organizes all weapons from Monster Hunter G, but it's now growing into a more complete wiki. [Visit the active app here!](https://mh1g-wiki.herokuapp.com/)

# Current State
I sourced all data from [mmpotato's MHG Analysis](http://infoseek_rip.g.ribbon.to/mmpotato.hp.infoseek.co.jp/codes/MHG/). Since I don't know Japanese very well, I used a plugin to translate everything, and consulted [Monster Hunter Freedom Unite Fandom Wiki](https://monsterhunter.fandom.com/wiki/Monster_Hunter_Freedom_Unite) to correct as many names as I could.

I based Monster Hunter 1 data largely on the NTSC-U release, removing anything I knew was not in the original Japanese release.

Feel free to reach out and submit any corrections, but keep the Issues tab purely for technical problems.

# Feature Checklist
- [ ] Blademaster Weapons, organized in a tree structure
	- [x] Great Swords
	- [x] Swords and Shields
	- [x] Dual Swords
	- [x] Lances
	- [x] Hammers
	- [x] Raw data with rough translation
	- [x] Correct weapon names
	- [ ] Correct material names
- [ ] Gunner Weapons
	- [x] Raw data with rough translation
	- [x] Correct weapon names
	- [ ] Correct material names
- [x] Checkbox to toggle MH1 and MHG weapons
- [ ] Armor List
	- [x] Raw data with rough translation
	- [ ] Correct armor piece names
	- [x] Correct armor skills
	- [ ] Correct material names
- [x] Armor Set Builder

# Developing
I've tried to keep this app as simple as possible: mostly static with a little JavaScript for interactivity.

## Requirements
- Node.js 10+

## Setup
1. `npm install` to prepare all necessary packages.
2. `npm run build` to compile all pages with MustacheJS.
3. `node app.js` to start a local Node.js server, hosted on port 8000.

# Resources
- [mmpotato's MHG Analysis](http://infoseek_rip.g.ribbon.to/mmpotato.hp.infoseek.co.jp/codes/MHG/)
- [Monster Hunter Freedom Unite Fandom Wiki](https://monsterhunter.fandom.com/wiki/Monster_Hunter_Freedom_Unite)
