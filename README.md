_Update notes for [Ring Robots](https://play.google.com/store/apps/details?id=com.tedsgames.ringrobots) on Google Play. Generated from the game's own `docs/update-notes.md` on every release — edits made here are overwritten by the next one._

# Ring Robots — update notes

What changed between builds, written for testers. The demo is the same package as the full
game with the demo flag on; it ends after the Tin Man and shows the rest locked.

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
