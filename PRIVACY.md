# WTCore Privacy Policy

_Last updated: 11 November 2026_

WTCore is a free, unofficial companion app for War Thunder, made by Nerd Bear Dev. It isn't made by, endorsed by or affiliated with Gaijin Entertainment, the makers of War Thunder.

**In short:** WTCore doesn't collect any information about you for its developer. It has no accounts, no ads, no analytics and no tracking. What you enter, and what it downloads, stays on your PC - unless you write a report to the developer yourself and press Send (see [Reports you send](#reports-you-send)).

## What WTCore keeps on your PC

- Your settings, such as your battle mode and how WTCore looks.
- The War Thunder nickname you enter as yours, and the nicknames you look up.
- What it reads from warthunder.com for those players (their public stats) and for squadrons, so it shows at once next time, with what changed since.
- Game data, news and pictures it has downloaded, so pages open quickly.
- Cookies set by War Thunder's websites while WTCore opens their pages, such as the one that remembers you passed their "are you human" check.

All of this stays in WTCore's data folder on your PC, and none of it is sent to the developer. If you send reports, the folder also keeps when you last sent them and a fingerprint of the last one's text (a short code worked out from it, not the text), so WTCore can hold you to its limits. _Settings > Saved data_ clears what WTCore downloaded and opens its data folder, and _Player stats_ forgets any player you've looked up (the × beside their name). Deleting the data folder removes everything WTCore kept, apart from its window's size and position, which it remembers in your Windows settings.

## Who WTCore connects to

To do its job, WTCore downloads public information from these services. As with any website you visit, they can see your IP address and what was requested, and their own privacy policies apply:

- **War Thunder's websites** (warthunder.com, wiki.warthunder.com and their picture servers, run by Gaijin Entertainment): news, game updates, events, vehicle data and pictures, squadron pages and players' public profiles. When you look up a player - or load your own stats - that nickname is sent to warthunder.com to open the profile.
- **GitHub** (Microsoft): the public War Thunder datamine, for vehicle data, and WTCore's own news feed. Copies of WTCore that didn't come from the Microsoft Store also get their updates from GitHub.
- **YouTube** (Google): the pictures of videos shown in War Thunder news. A video itself only opens if you click it, in your browser.
- **Discord** (Discord Inc.): only when you send a report - see below.

While War Thunder runs on your PC, WTCore also reads the game's own status page on your PC (`localhost:8111`) to know whether you're in a battle. That never leaves your PC.

## Discord

If Discord is running and Discord status is on (_Settings > Discord_ - on unless you turn it off), WTCore tells the Discord app on your PC what you're doing in War Thunder: whether you're in the hangar or in a battle, and the vehicle you're using. Discord shows it on your profile, under Discord's privacy policy. To show the vehicle's picture there, its public picture from the War Thunder wiki is sized to fit by wsrv.nl, a free image service. You can turn this off at any time in _Settings > Discord_.

## Reports you send

_Support > Report_ lets you tell the developer about a bug, wrong data, an idea or a translation mistake. Nothing is sent until you press **Send**, and only what the window lists under _What gets sent_ goes, with your comment:

- what it's about (the kind you picked) and the comment you wrote,
- unless you untick them: WTCore's version, the kind of copy (a release, the Microsoft Store's or a development one), your Windows version, WTCore's language and the page you came from (which of WTCore's pages, like `/tree` for the Tech tree - never anything you typed into it),
- only if you tick it: your War Thunder nickname from _Settings_.

Never your stats, files or folders on your PC, its name, or anything else. The report is posted to a channel on the developer's Discord server, through a Discord webhook, with a short reference code; Discord sees your IP address like any website does, and its privacy policy applies. Only the developer and whoever they let into that channel can read it. Reports are kept there for as long as the developer needs them to fix things; to have one removed, [open an issue on GitHub](https://github.com/nerd-bear/WTCore/issues) with its reference code. To keep the tool from being misused, a PC can send one report every few minutes and a handful a day, and not the same comment twice in a row.

## Microsoft

WTCore's window runs on Microsoft Edge WebView2, and copies from the Microsoft Store are installed and updated by the Store. Both are covered by Microsoft's privacy statement.

## Children

WTCore doesn't collect information from anyone, including children. A report holds only what its sender chose to send.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions about this policy or WTCore: [open an issue on GitHub](https://github.com/nerd-bear/WTCore/issues).
