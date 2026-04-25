<img width="64" height="64" alt="triple20symbol-light" src="https://github.com/user-attachments/assets/2032882d-4295-4f45-82e8-7511b431aca7" />

# Triple Twenty — Support & User Guide

Triple Twenty is a darts score tracker designed for every game night. Whether you're playing solo against a bot, passing the phone with friends, competing head-to-head over Wi-Fi, or playing turn-by-turn through Game Center, Triple Twenty keeps score so you can focus on the board.

---

## Game Modes

### Cricket (Simple) — *Free*
Hit numbers 15–20 and Bull to close them. Each target needs 3 marks to close (singles = 1 mark, doubles = 2, triples = 3). No points are scored — the first player to close all 7 targets wins.

**How to play:** Tap a target on the scoreboard to record a mark. Tap "Miss" if no targets were hit. Tap "End Turn" when your darts are recorded. Tap "Undo" to remove the last mark.

### Random Cricket — *Free*
Same rules as Cricket (Simple), but with randomly selected targets. Instead of the standard 15–20 and Bull, 7 random numbers are chosen at the start of each match. First player to close all 7 wins.

### Cricket — *Pro*
The full-featured version of Cricket with points scoring. Hit numbers 15–20 and Bull to close them. Once you've closed a target, additional hits score points equal to that number — but only if your opponent hasn't closed it yet. First player to close all targets with equal or more points wins.

**Color guide on the scoreboard:**
- **Green tint** — Target needs marks (tap to close)
- **Blue tint** — Target is closed and you can score points (tap for points)
- **Red tint** — Opponent has closed this target and can score on you
- **Grey tint** — Target is closed by all players (dead)

### 301 — *Pro*
Start at 301 points. Each turn, throw 3 darts and subtract your score. Reach exactly 0 to win. Going below 0 is a "bust" — your turn's score doesn't count and your score resets to what it was before the turn.

### 501 — *Pro*
Same as 301, but starting at 501 points.

**Countdown options (301 & 501):**
- **Double In** — Your first scoring dart must be a double to start counting
- **Triple In** — Your first scoring dart must be a triple to start counting
- **Double Out** — Your final dart must be a double to win
- **Triple Out** — Your final dart must be a triple to win

**Checkout suggestions:** When your remaining score is achievable in 3 darts or fewer, a suggested checkout route is displayed above the number board.

### Round the Board — *Free*
Hit every number in order: 1, 2, 3… all the way through 20, then Bull. Singles advance 1 target, doubles advance 2, and triples advance 3 (e.g., hitting Triple 5 when you're on 5 jumps you to 8). Only hits on your current target count — everything else is a miss. First player to complete all 21 targets wins.

---

## Play Modes

### Local (Pass & Play)
Play with 2–4 players on a single device. Pass the phone between turns. Supports all game modes.

**Players:** Enter names for each player on the setup screen. Tap "Add Player" for 3- or 4-player games.

**First player:** Tap "Throws First" on the setup screen to change who goes first.

### Bot
Play solo against a computer opponent. Available in local mode for all game modes.

**Difficulty levels:**
- **Beginner** — The bot misses very frequently, ideal for new players learning the game
- **Easy** — The bot misses frequently and makes basic decisions
- **Medium** — A balanced challenge for casual players
- **Hard** — The bot plays strategically with higher accuracy

### Nearby (Wi-Fi)
Play head-to-head with another device on the same Wi-Fi network. One player creates a match and shares a 6-character code; the other enters it to join.

**To create a match:**
1. Select "Nearby" as the play mode
2. Choose "Create" under Match Role
3. Enter your name and tap "Create Match"
4. Share the 6-character code with your opponent

**To join a match:**
1. Select "Nearby" as the play mode
2. Choose "Join" under Match Role
3. Enter your name and the 6-character code
4. Tap "Join Match"

**Reconnection:** If the connection drops during a nearby match, the guest will automatically attempt to reconnect. The host continues to listen for the guest. Both players' progress is preserved.

### Game Center (Async)
Play turn-by-turn with friends or random opponents through Apple's Game Center. Both players must be signed into Game Center on their devices. Take turns at your own pace — you'll receive a notification when it's your turn.

**To start a Game Center match:**
1. Select "Game Center (Async)" as the play mode
2. Enter your name and tap "New Async Match"
3. Invite a friend or start a match with a random opponent
4. Play your first turn — your opponent will be notified

**To view and resume active matches:**
1. Tap "View Active Matches" on the setup screen
2. Your matches are listed with turn status (your turn or waiting)
3. Tap a match to continue playing

**How it works:**
- After you complete your turn, the board locks and shows "Waiting for opponent's turn"
- When your opponent takes their turn, you'll receive a push notification
- The board unlocks automatically when it's your turn again
- You can pause and return to any active match at any time

**Score corrections in async:** You can edit your own past turns from the match history panel. Corrections are synced to your opponent's device automatically. You cannot edit your opponent's turns.

**Quitting a match:** Swipe left on a match in the Active Matches list to quit. Your opponent will be notified that you left. Completed matches are automatically removed from the list.

**Note:** Game Center must be set up on your device. If it's not configured, the async options will be disabled with a message to sign in via Settings.

---

## Scoring & Input

### Cricket Modes
The scoreboard is interactive — tap directly on a target to record marks. Each tap records a single mark. The scoreboard updates in real time to show your progress.

- **Mark symbols:** / = 1 mark, X = 2 marks, ⊗ (circled X) = 3+ marks (closed)
- **Miss:** Tap the "Miss" row at the bottom of the scoreboard to record a miss and end your turn immediately
- **End Turn:** Tap to submit your marks and pass to the next player
- **Undo:** Remove the last mark you entered

### Countdown Modes (301 / 501)
Use the number board to enter each dart:

1. **Select a multiplier** — Single, Double, or Triple (defaults to Single)
2. **Tap a number** (1–20), Bull, or Miss
3. Repeat for up to 3 darts per turn
4. Tap **End Turn** to submit

The running total for your turn is displayed alongside the dart badges. If your total would take you below zero, "BUST" is displayed and the turn won't count.

### Round the Board
Uses the same number board as countdown modes. Tap the number you hit — only hits on your current target will advance your position.

### Score Corrections
Made a mistake? You can edit past turns from the match history panel.

- **Open history:** Tap the history icon during a match
- **Edit a turn:** Tap a turn to view its darts, then tap a dart to remove it
- **Delete a turn:** Tap a turn, then tap "Delete Turn" to remove the entire turn
- **Async restriction:** In Game Center async matches, you can only edit your own turns — not your opponent's

All corrections recalculate the game state automatically.

---

## Features

### Voice Announcements
Turn announcements speak the next player's name at each turn change. Useful for local multiplayer so you don't have to look at the screen.

**To enable:** Settings → Turn Announcements → On

**Voice selection:** Choose from available system voices in Settings → Voice. Download additional voices from your device's Settings → Accessibility → Speech.

**In remote/Game Center play:** The voice says "Your turn" only when it becomes your turn. It does not announce when it's the remote opponent's turn.

**Bot matches:** Voice announcements are automatically silenced during bot matches since it's a single-player experience.

### Match History
View all completed matches with results, scores, and dates. Access from the home screen via the "History" button. Game Center async matches are saved to your history when they complete.

### Player Stats
Track your performance across all matches. View per-player statistics from the "Player Stats" button on the home screen.

### Achievements
Earn achievements as you play. View your progress by tapping the trophy icon in the top-left corner of the home screen. Achievements are synced with Game Center when signed in.

### Win Screen Animation
When a player wins, a dart flies across the screen and strikes a bullseye target on the trophy — with confetti to celebrate the victory.

### Resume Match
If you leave a local or nearby match in progress, you can resume it from the home screen. The "Resume Match" button appears when a saved match is available.

**Game Center async matches:** You can pause and return to async matches at any time from the "View Active Matches" screen. Your progress is saved on Apple's servers.

### Version Info
The current app version and build number are displayed at the bottom of the Settings screen.

---

## Pro Upgrade

Triple Twenty is free to download and play with three game modes:
- Cricket (Simple)
- Random Cricket
- Round the Board

The **Pro Upgrade** ($2.99, one-time purchase) unlocks:
- Cricket (with points scoring)
- 301
- 501

To restore a previous purchase, go to Settings → Restore Purchases.

---

## Troubleshooting

### Nearby multiplayer not connecting
- Make sure both devices are on the same Wi-Fi network
- Check that Local Network permission is granted (Settings → Triple Twenty → Local Network)
- Try creating a new match with a fresh code
- Restart the app on both devices

### Game Center not working
- Make sure both players are signed into Game Center (Settings → Game Center)
- Check your internet connection
- Try restarting the Game Center matchmaker

### Game Center async — turn not updating
- The opponent's turn may take a moment to propagate through Apple's servers
- Pull down to refresh on the Active Matches screen
- Make sure push notifications are enabled for the app
- Try closing and reopening the match

### Game Center async — stuck matches
- Swipe left on the match and tap "Quit" to leave it
- If the match keeps reappearing, the quit will process on the next server sync

### Voice announcements not playing
- Make sure announcements are enabled in Settings → Turn Announcements
- Check that your device is not in silent mode
- Try selecting a different voice in Settings → Voice

### App showing stale "Resume Match" button
- If the button doesn't lead to a valid match, tap it once — the app will clear the stale data automatically

---

## Contact & Support

If you need help or want to report a bug, reach out via email:

**support@tripletwenty.app**

Visit us at [tripletwenty.app](https://tripletwenty.app)

We'd love to hear your feedback — if you enjoy Triple Twenty, please leave a review on the App Store!

---

## Privacy

Triple Twenty does not collect, store, or share any personal data. All match data is stored locally on your device. Game Center features use Apple's infrastructure — refer to Apple's privacy policy for details on Game Center data handling.
