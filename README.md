<p align="center">
  <img src="media/icon.png" width="128" alt="ritsu! app icon">
</p>

# ritsu!

A companion app for osu! players. ritsu! shows your stats, top plays, rank
history and friends in one place on your phone.

## join the iOS beta

ritsu! is in public beta on TestFlight.

1. Install [TestFlight](https://apps.apple.com/app/testflight/id899247664) on your iPhone.
2. Open the [beta link](https://testflight.apple.com/join/UsvCNMp7).
3. Tap **Accept**, then **Install**.

Requirements: an iPhone on iOS 15 or later. iPad is not supported yet.
Beta spots are limited; if the link says the beta is full, check back later
or watch this repository for updates.

## features the app currently has

- **Home:** pp, global and country rank, accuracy, play count, at a glance.
- **Stats:** rank and pp history (via [osu!track](https://ameobea.me/osutrack/)), grade counts, mods in your top plays.
- **Plays:** your top and recent plays.
- **Maps:** search beatmaps; open a map for its difficulty stats and the song on Spotify (best effort matching. it does it's best)
- **Social:** add friends with a private friend code and compare progress (kinda borked for now, under dev)
- All four modes: osu!, taiko, catch and mania.

You sign in with your osu! account on osu! web. ritsu! never really sees
your password its just a osu! connector per se

## report bugs or suggest something

- **Bugs:** [open a bug report](../../issues/new?template=bug_report.yml).
- **Ideas:** [open a feature request](../../issues/new?template=feature_request.yml).
- **Quick questions and chat (if you wanna get in direct touch w me):** Discord (invite coming soon). 

you can also send feedback from inside TestFlight ofc: take a screenshot while
using ritsu! and tap **Share Beta Feedback**.

also, make sure if you're opening an issue, that issue hasn't been opened before (or similar ones)

## here's a quick demo if you wanna see (this is build 3.1.0-1 public beta)



https://github.com/user-attachments/assets/21efa22c-9e68-4839-8c39-7a5800bb601c


what's new with 3.1.0-3[^1]:
 - UI updates. apparently, a lot of people thought the light bloom and the gradient in general were "hallmarks of ai slop" which is fair but slop implies the app doesn't work, which it does so idk. 
 - Hit distribution percentage bug fixed in the stats history page
 - redesigned profile page (Me)
 - brought home cards to consistent sizes
 - Detailed map display now collapses to header on scroll, previously did not in 3.0.0-4
 - Personal bests cards removed, set up redesigned
 - Added Sentry user feedback, prepping for Android release
 - Laid foundation for Widgets and customizable accents for the app theme, will ship in next minor version
 - Play time showing 0h on the Me tab is fixed
 - The stats history graph transitions are fixed

## features in pipeline
- [ ] Widget Support (choices bw pp, Global Rank, ii, or country rank) - Home screen (+ lock screen for iOS)
- [ ] Compatibility for iPad & iPhone Duo
- [ ] Customizable two tone accents for app theming
- [ ] Android release (public beta)
- [ ] Play-style and improvement analysis (ferry ii)
- [ ] Mutualify integration (user feedback, i have to look into the public api for this before committing to implementing)
- [ ] Light and dark mode toggles


## Privacy

Read the [privacy policy](https://github.com/samvictordr/ritsu-docs/blob/main/PRIVACY_POLICY.md).
basically no ads, no analytics, no tracking, except for Sentry which we use for error mitigation and nothing else. sentry collects strictly non-personal stuff and data is stored under EU regulations regardless

## Not affiliated with osu!

ritsu! is an independent, free fan project. It is not affiliated with, endorsed by, or sponsored by ppy Pty Ltd. "osu!" is a trademark of ppy Pty Ltd.

[^1]: Version 3.1.0-3 is basically what was distributed in the public beta test as 3.0.0-5, I wanted to clean up my version tags so it was made into 3.1.0-3. 3.0.0-5 will be expired from testing soon, build 4 of v3 should have already been expired at the time of this edit.
