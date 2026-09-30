_Update notes for [Ring Robots](https://play.google.com/store/apps/details?id=com.tedsgames.ringrobots) on Google Play. Generated from the game's own `docs/update-notes.md` on every release — edits made here are overwritten by the next one._

# Ring Robots — update notes

What changed between builds, written for testers. The demo is the same package as the full
game with the demo flag on; it ends after the Tin Man and shows the rest locked.

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
