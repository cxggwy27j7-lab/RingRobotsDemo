_Update notes for [Ring Robots](https://play.google.com/store/apps/details?id=com.tedsgames.ringrobots) on Google Play. Generated from the game's own `docs/update-notes.md` on every release — edits made here are overwritten by the next one._

# Ring Robots — update notes

What changed between builds, written for testers. The demo is the same package as the full
game with the demo flag on; it ends after the Tin Man and shows the rest locked.

## 1.5.0 (build 8) — 8 October 2026

Screens arrive faster on a budget phone, a GRAPHICS setting sharpens the desktop, the demo signs off with a thanks card, and a title league waits past The Furnace.

**New**

- **The Belt.** Six title fights after The Furnace, each a replay of a back-half boss for a
  flat prize at an entry fee of three quarters of it: Reigning Warden, Mirror, Carrier,
  Keeper, Ash and Iron and Furnace. Each clear earns a title; all six earn CHAMPION. Nothing
  before The Furnace changes, and a player who never enters loses nothing.
- **Faster screens.** Every screen now builds once on the way in, after its save has
  loaded, and measures its text without drawing it. On a budget phone the pause between
  screens is a quarter to a half of what it was.
- **A GRAPHICS setting** in Options: AUTO, LOW, MEDIUM, HIGH. HIGH draws at your screen's
  real pixels, which is the fix for the soft look on a desktop; LOW draws fewer pixels for a
  phone that needs the frames. AUTO picks HIGH on a desktop and MEDIUM on a phone, then
  watches your first fight once and drops a step if the frames cannot keep up, telling you so.
- **The demo's last word.** Past the Tin Man the demo now shows a short thanks card with a
  SEND FEEDBACK button that opens your mail app, instead of a paragraph in the level card.

**Balance, from the rig**

- The Belt takes about forty percent of the spare money a finished campaign used to bank,
  most of it at the Reigning Mirror, which arrives at a 28% win rate and is meant to.

**Fixed**

- The campaign ladder opens with your current rung on screen, not scrolled off the top.
- The results screen draws its winnings and honours on the first frame rather than a
  blink later.

## 1.4.0 (build 7) — 5 October 2026

A rewards screen worth reading, a fight with some punch, and the back half of the ladder costs a little less and pays a little less.

**New**

- **The results screen.** Under the rosters: your purse itemised (prize, a flawless bonus,
  repairs), every part you fielded with its level and the experience this fight added, and
  a third panel that shows the part you just won with a FIT IT NOW tap, or the next rung
  with its fee and prize, or the fight's honours.
- **Flawless bonus.** Win without losing a machine and the prize pays 10% more.
- **Juice.** Heavy hits and wrecks shove the view, a wreck flashes and sounds heavier, and
  the kill that decides a fight gets a beat before the banner. MOTION in Options turns all
  of it down to none.
- **The main menu card shows your campaign machine** and the campaign shop's unclaimed count,
  not the skirmish garage's.
- **The reward card shows the part itself**, drawn as the garage draws it.
- **Options in two columns** on a phone or desktop, so the whole list is a page or two.
- **Four-side fights fit on a phone.** The team rows pack around the buttons instead of
  stacking down the screen, and the camera opens on every squad.

**Balance, from the rig**

- EMP Projector is 350 bolts, down from 380.
- Prizes and fees from Rust Budget to Ash and Iron are 15% lower, so a finished campaign
  banks less spare money. Nothing before The Warden changes.

**Fixed**

- FIGHT AGAIN from a campaign result now charges the rung's entry fee, as the ladder always
  did; if you cannot pay it, you land on the ladder with the rung selected.
- The campaign opens on the rung you are at, not First Blood.
- The level card's rules, squad and footer no longer print over each other on a phone, and
  every number carries its thousands separator.
- NEXT UP and the ladder say how far short of a fee you are.
- The arena picture on the campaign card no longer sits on the arena's name.
- A long machine name on the results roster no longer runs into its numbers, and a four-side
  roster keeps every team name in full.
- The ♪ button no longer sits on the first team row, and a wide player name shrinks its row
  rather than running under the buttons.
- Drones no longer pull the camera toward wherever they fly.
- Winning a module with no machine that can carry it no longer lets it be fitted anyway.
- Updating from an older build shows what changed, once, on the main menu, and WHAT'S NEW in
  Options opens the same card any time, with a link on to the public notes.
- The three buttons under a result share one weight, so FIT IT NOW stands out on a reward.

## 1.3.0 (build 6) — 1 October 2026

A new flak gun, the Lighthouse boss with its own beam, slower treads, and the fixes from the second bug hunt.

**New**

- **Hailstorm.** A medium-mount flak gun that fires real rounds at incoming shots and bursts
  them in the air. It swats volleys and drones; a mortar shell lobbed over it gets through.
  Priced at 300. The demo shows it on the shelf as FULL GAME.
- **PRIVACY POLICY and WHAT'S NEW** rows in Options, each opening the page in your browser.

**Balance, from play**

- The Lighthouse's charge now bleeds at the standard rate in your hands. The boss turrets on
  that level carry their own beam, the Lighthouse Beacon, which bleeds faster so the level
  stays beatable.
- Treads and wheels turn a quarter slower, so the hull reads as rolling rather than racing.

**Fixed**

- Tapping NEXT in the tutorial while the fight's music panel was open only closed the panel
  and left the fight paused until a second tap. One tap now.
- The fire-mode prompt at the top of a fight could sit on top of a boss's health bar, or
  under the music panel. It now yields to both.
- The "now playing" card could cover the Campaign footer and the garage's DEPLOY SQUAD bar.
- A Scrap Torch that was still burning at the instant a fight ended could keep humming over
  the results screen.

## 1.2.0 (build 5) — 1 October 2026

Fire modes, wheels that turn, Scrap Docks rebuilt, a new icon, and five balance changes from play.

**New**

- **Fire modes.** Hold one of your machines in a fight to switch it between focus fire (every
  gun on one target) and independent fire (each turret picks its own). A prompt at the top
  says what changed and a ring mark shows which machines are independent. Each machine's
  default is set on its style tab in the garage.
- **Manual style.** A fight style that never moves on its own: it holds where it stands or
  where you drag it, and fires at what it can see.
- **Wheels and tracks move.** Treads scroll and wheels spin on every wheeled or tracked hull
  drawn large enough to read it.
- **Scrap Docks looks like a dock.** Container stacks, a quay with water beyond it, cranes,
  bollards and crates, in its own cold steel and sodium light.
- **Hits read as what hit you.** Sparks, scorches, flame, acid and EMP each land differently.
- **A new icon and feature graphic**, and the launcher icon on your phone changes with them.
- **HOW TO PLAY** is bigger and in the game's own style.

**Balance, from play**

- Siege Mortar: reach 440 to 520, and it scatters around its aim point like a real mortar.
- Drones dodge half of ordinary shots and a quarter of beams; point defence still swats them.
- A charging weapon bleeds its charge instead of losing it all when the target is lost. The
  Lighthouse boss bleeds faster so the level stays beatable.
- The Carrier boss holds its rifle's reach instead of rushing the line.
- Flashpoint is nine flame machines with an anchor.

**Fixed**

- Title-screen machines no longer overlap on a desktop window.
- Options notes no longer run past the scroll bar.
- RESET CAMPAIGN PROGRESS offers the tutorial again.
- Walls on the fortified levels meet cleanly at corners and edges, and read the same from
  either side.

## 1.1.0 (build 4) — 29 September 2026

**New**

- **Tutorial.** A fresh install walks you through the garage (buy a frame, fit a weapon, fit
  armour) and your first fight (focus the squad, give one machine an order, drag one to
  reposition, pause and speed). SKIP is always there. Existing players can run it any time
  from HOW TO PLAY, "PLAY THE TUTORIAL".
- **Profile.** A PROFILE screen on the main menu with your name, your team colour and a list
  of titles. Titles are earned by clearing levels, beating bosses and hitting milestones;
  wear the one you like and it shows in fights and on the results screen.
- **Music.** Seventeen tracks on shuffle across the whole game, a MUSIC row in Options, a
  small "now playing" card when a track starts, and a music button in the fight with
  previous, pause and next.
- **Studio card and title screen.** The Ted's Games ident on cold start, then a tap-to-start
  title.
- **Sounds.** Torches hold a loop while firing and a burning machine crackles.

**Fixed**

- The SELL button on the weapons shelf was hard to hit: a tap just past its edge fitted the
  part instead of selling it, and on a long shelf the scrollbar stole the tap. Both fixed,
  from the first tester's report.
- Six of the seven main-menu rows needed two taps on a touchscreen. One tap now.
- The boss's health bar sat under the HUD buttons.
- The garage shelf now steers you to every missing part after a purchase, not only the
  first.
- The skirmish dial column shows a scrollbar when it overflows.
- A second machine that has nowhere to deploy says so, instead of a silent dot.
- Flashpoint retuned: nine flame machines with an anchor instead of five identical ones, so
  reach alone no longer walks it.

**Under the hood**

- Every atlas repacked: the game holds less than half the texture memory it did, which is
  what matters on a cheap phone.
- Menu rows, options, and every other screen wait on themselves properly, so nothing
  reads as frozen for a second on a slow device.

## 1.0.2 (build 3) — 27 September 2026

- A FEEDBACK row in Options opens a mail template with the build number filled in.
- The demo shows the drone bays, the Lighthouse and the EMP on the shelf as FULL GAME and
  never fields them against you.

## 1.0.1 (build 2) — 27 September 2026

- Pressing ? during a fight no longer freezes the game.
- The Options screen scrolls, so RESET CAMPAIGN PROGRESS is reachable on a phone.
- Pinch and mouse-wheel zoom in fights and in the arena editor.

## 1.0 (build 1) — 26 September 2026

- First upload to internal testing. Campaign to the Tin Man, weekly challenges, skirmish
  with up to four sides, the arena editor with shareable map codes.
