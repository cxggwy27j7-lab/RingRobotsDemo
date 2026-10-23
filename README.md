_Update notes for [Ring Robots](https://play.google.com/store/apps/details?id=com.tedsgames.ringrobots) on Google Play. Generated from the game's own `docs/update-notes.md` on every release — edits made here are overwritten by the next one._

# Ring Robots — update notes

What changed between builds, written for testers. The demo is the same package as the full
game with the demo flag on; it ends after the Siege (the end of the Main Card, from 1.6.0; it was the Tin Man before)
and shows the rest locked.

## 1.9.1 (build 13) — 24 October 2026

Beta testers can now unlock the base game and each pack with their own codes.

**New**

- **Tester codes.** If you are testing the beta, you will be sent your own codes: one for the base
  game and one for each pack. In Options, tap BETA on the IMPORT SAVE row and enter your BASE
  GAME code first, then any pack codes; each unlocks that part of the game on your device. The
  unlocks last for the test and end when the game launches. Codes are personal, so please do not
  share them.

## 1.9.0 (build 12) — 24 October 2026

Your campaign is safe when you empty a mount, every part in the garage can be compared before you fit it, and the map editor draws the fight's own art.

**Fixed**

- **A lost campaign.** Emptying a weapon mount or a module slot could leave a save the game
  could not read, and the next screen that saved wrote a fresh campaign over it: 700 bolts and
  nothing else. The save now reads back with the gap in it. If the game ever meets a save it
  cannot read again, it keeps a copy aside rather than writing over it, and RESEARCH refuses to
  spend until it is sorted.
- **The garage stuck on frames.** After BUY A FRAME, picking a machine or a slot, or going to
  RESEARCH and back, now returns the shelf to that machine's parts.
- **The main menu's scroll bar** can be seen now, with an arrow at each end that lights when
  there is more to scroll to.

**New**

- **Compare before you fit.** Every part on the shelf, bought or already in your workshop,
  opens a card that sets it against the part on that mount: each stat NOW and NEW, green with an
  arrow up where the new part is better and red with an arrow down where it is worse. A part you
  own says CONFIRM, a part you would buy says BUY & FIT, and CANCEL changes nothing.
- **The map editor draws real fight art.** Walls, blocks, barrels, fire, acid, vents, barriers
  and decor are drawn with the arena's own sprites for its terrain set, so a map looks in the
  editor the way it will in a fight. Decor on your own maps now sits in the middle of its cell in
  a fight too, where it used to sit half a cell off.
- **Credits.** Sammy, the MVP of testers, found the lost-campaign bug above and asked for the
  compare card. Thank you.

## 1.8.0 (build 11) — 21 October 2026

Two new bikes join the garage, the map editor is reworked, and research, weight limits, objectives and the pack campaigns arrive.

**Fixed**

- **The map editor, reworked.** Every tool is an icon tile, always on screen. A drag paints
  every cell it crosses, with no gaps on a fast stroke. Tap a piece to select it, then drag it to
  move it; any other drag paints. One finger paints even when zoomed, two fingers pan. UNDO goes
  all the way back and REDO returns. A new map starts with its spawn lines drawn, the check runs
  as you edit, and PROBLEMS lists what is wrong in full. The map's size, grid and terrain live
  under SETTINGS. Your map is kept as a draft when you leave, and NEW starts fresh.
- **The status bar, again.** On a phone that kept its clock and battery over the game after 1.7.0,
  the app now declares fullscreen at the window itself and re-hides the bars whenever the system
  shows them. If yours still shows the bar, send feedback with INFO on so we can see where it sits.

**New**

- **Courier and Despatch.** Research Bikes II to unlock the Courier, then Bikes III for the
  Despatch. Each adds a faster, heavier bike with a different weapon loadout.
- **The Buggy at the start.** The Buggy now appears on the free Wheeled I root, alongside the
  Trooper.
- **Research.** The shop is earned a branch at a time. Every fight pays research points, shown
  on the results card, and a RESEARCH page off the garage and the ladder sells nodes like LASER
  II or TRACKED CHASSIS III, each opening the parts of that class and tier. Locked parts on the
  shelf say which node they wait on; tapping one takes you there. An existing save keeps every
  part it owns and everything it could already have bought.
- **Weight limits.** Every frame has a base weight, and a machine's tonnage is that plus what
  it carries, shown on its card and on the deploy bar. Two fights cap your side's tonnage:
  Weigh-In in the Proving and Kindling in the Burn. A lightly equipped heavy counts as a medium.
- **Objectives.** Three new fights are won by holding ground or beating a clock, not only by
  wrecking everything: The Hill in the Circuit, Three Points in the Proving, Against the Clock in
  the Burn. Zones show on the floor, a bar on the HUD shows who holds what, and a tap on a zone
  sends a machine to it. The arena editor can place zones and the map code carries them.
- **The Legion.** A walker campaign of its own, fifteen fights across three leagues, every one
  on legs: a maze, a hill, points, a clock, two weight limits, a hunt, a line to break and a
  Triarii pair at the end. It opens from a card on the campaign screen once you own The Legion
  and have researched Walkers I, keeps its own wallet and progress, and shares your garage and
  research. You pilot your lead walker by default.
- **Research sells ways to fight.** Beyond parts, the tree now has bounded upgrades for light
  frames, medium frames, light guns and walker legs, a few percent at a time and never past a
  quarter, and two doctrines: Flanking, and Style Tuning, which opens an engagement-range slider
  on a style. Focus fire stays free.
- **Speed is worth something.** A shot can now miss a machine crossing its line, more often for
  slow guns and fast targets, so a light hull at full tilt sheds about a third of a mortar's fire
  and almost none of a railgun's. A machine standing still is hit as before.
- **The grapple** (in The Legion): a Pin for light hulls, an Anchor for mediums and a Hook for
  heavies. A line holds a heavier machine still while your friends hit it, or reels a lighter one
  in; it parts under fire, at a wall, at the end of its hold, or to point defence.
- **The Hive.** The Drone Pack now has a campaign of its own. Nine fights in three leagues for
  flights rather than guns: every machine you bring carries a drone bay, and the enemy is built to
  be flown over or built to shoot a flight down. It opens from a second card beside the Legion's
  on the campaign screen once you own the Drone Pack and have researched a drone bay.
- **War Games.** The missions pack is now a campaign of its own: twenty-four missions in four
  leagues, each with a rule beyond the kill. It opens from the PACKS button on the campaign screen
  once you own the pack and have cleared The Hill. It uses your own garage, keeps its own bolts, and
  has its own titles and a three-part story, ending at The Gauntlet.
- **Every ladder is one tap away.** The campaign screen has a switcher for the campaign, the
  Legion, the Hive and War Games, each its own list that remembers where you were, and it is there
  in the free game too. The first fight of each pack ladder is a free trial: the Legion and the
  Hive lend you a machine of their own to fight it, beside your own garage, and a first clear pays
  like any other.
- **One purchase for everything.** UNLOCK EVERYTHING sits on the thanks card beside UNLOCK THE
  BASE GAME: one payment that opens the base game and every expansion, the ones that exist and the
  ones still to come. It brings a gold finish for your machines, switched in Options by the GOLD
  chip on the MOTION row, and the title PATRON.
- **The research page has a rail** down the left, like the campaign's: WEAPONS, FRAMES, ARMOUR,
  MODULES, UPGRADES and DOCTRINE, each its own list that remembers where you were.

**Changed**

- **A quieter title screen.** The tagline has been removed.
- **Locks say what opens them.** A locked part on the shelf reads BASE GAME, THE LEGION or THE
  DRONE PACK instead of FULL GAME, ahead of the full game and its packs arriving on the store.
- **4X fight speed** is part of the base game; the free game runs at 1X and 2X.
- **The Hangar** module joins the drone pack with the drone bays, so it shows locked in the free game.

## 1.7.0 (build 10) — 16 October 2026

Six walking mechs enter the ring, the results card says what you have left, feedback can carry game info if you choose, and the status bar stays out of the way.

**Fixed**

- **The status bar on some phones.** On a Nothing Phone 3a Pro the clock and battery stayed on
  screen over the game. The app now hides the system bars the way current Android asks, and the
  camera notch strip is used rather than blacked out. A swipe from the edge still shows the bars
  for a moment.
- **The results card shows your wallet.** The purse now ends with a WALLET line: the bolts you
  have after the prize, the bonus and the repairs, in the campaign and in a challenge.

**New**

- **Walkers.** Six mechs on legs: the Strider, Centurion and Titan, and the legion's Velites,
  Hastati and Triarii. The legs walk where you send them and the body turns to aim, twisting
  only so far before the legs must follow, so a walker can be flanked. Arms carry light and
  medium guns that swing a little; shoulders carry fixed guns that point where the body does.
  Three new fights put them against you: Hinge Point in the Circuit, The Testudo in the
  Proving, Stampede in the Burn. In the demo they show on the shelf, locked.
- **Guns drawn to size.** A light gun is drawn smaller than a heavy one on every hull, so you
  see more of the machine under it.
- **Feedback with game info, if you want.** SEND FEEDBACK in Options has an INFO chip; with it
  on, the mail draft includes your build, device, screen, graphics and control settings, how far
  you are up the ladder and the game's last few error messages, for you to read before you send.
  Off by default, never your save, and nothing is sent unless you send it. The demo's thanks card
  has the same choice.

## 1.6.0 (build 9) — 14 October 2026

The demo opens the next circuit, the game tells its story, and a save code carries your progress.

**New**

- **Six screens redrawn.** The campaign ladder shows each fight's arena, opposition, purse
  and reward on one card with TO THE RING as the button; the challenges screen says what is
  done this week and which of your machines qualify; the profile has your record, your titles
  lit by league, and the story so far; Options is six groups of plain rows with a line under
  each saying what it does; the skirmish screen shows both sides as thumbnails over the arena;
  HOW TO PLAY has a drawn diagram on every point.
- **A story.** Scrap City, Season 3. Short cut scenes when you arrive somewhere new: the first
  time a card opens, the first time a boss is on the ladder, and the Furnace. Tap to advance,
  SKIP any time, and a STORY page on your profile to read them again.
- **A save code.** EXPORT SAVE in Options copies one code for all your progress; IMPORT SAVE
  on another copy of the game pastes it back. It is how a demo save carries into the full game.
- **PILOT.** Drive one of your own machines yourself: a PILOT chip on the deploy bar picks
  which. A stick on the left, a button per weapon on the right, LOCK to pick a target; tap a
  weapon twice to keep it firing until the target falls. The view pulls in close on your
  machine. Options has a PILOT CONTROLS row: BUTTONS, or TWIN STICK, a second stick that aims
  and fires every gun where you push it. WASD, number keys and the mouse on a desktop. The
  rest of your squad fights as it always has.
- **The demo now runs to the end of the Main Card:** fifteen levels, two bosses.

**Balance, from the rig**

- Flak Curtain's three Siege Frames carry a Scrim Field each; they were the only machines in
  the Circuit without a shield. Long guns beat it as before; a short-range squad has a harder
  time of it.

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
