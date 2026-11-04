# 🎾 CourtScore — Tennis Scoreboard & Tournament Manager

**Less time counting scores, more time enjoying tennis.**

CourtScore is a free, mobile-friendly tennis scoreboard and tournament manager designed for casual games, friendly competitions, and tennis communities.

Built with HTML, CSS, and JavaScript, CourtScore automatically calculates tennis scores, manages player rotations, generates tournament matches, and tracks results — all without requiring an account or backend.

## 💡 Background

CourtScore started from a simple problem: keeping track of scores during tennis matches can be confusing, especially when playing doubles, rotating partners, or organizing multiple matches in one session.

Players should be able to focus on enjoying tennis rather than manually counting points, remembering previous results, or deciding who plays next.

CourtScore was created to simplify these activities through an accessible digital scoreboard and tournament management system.

The goal is simple: **make tennis scoring and match organization easier for everyone.**

## ✨ Features

### 🎮 1. Game Modes

CourtScore supports two game modes:

| Mode | Description |
|---|---|
| Casual Game | Track scores, manage players, and play multiple friendly matches |
| Competitive Game | Organize tournaments, generate matches, track standings, and determine winners |

### 🎾 2. Casual Game

Designed for regular tennis sessions and friendly matches.

**Match Setup**
- Singles (1 vs 1) and Doubles (2 vs 2).
- Flexible match formats, including Short Set, One Set, Best of 3, Best of 5, and Super Tie-break.
- Configurable game scoring and deciding-set rules.
- Dynamic Match & Scoring Rules.
- Conditional fields based on selected match format.
- Default setup: Doubles and Short Set.

**Player Management**
- Register players before starting.
- Add new players during an ongoing session.
- Select Fixed Partner or Random Partner for Doubles.
- Choose fixed partners manually or randomize them once.
- Prevent duplicate player selections across teams.
- Keep the current match unchanged when new players are added.

**Match Scoring**
- Automatic point, game, and set calculations.
- Deuce and Advantage scoring.
- Tie-break and Super Tie-break support.
- Live scoreboard and serving indicator.
- Undo and Restart Match.

**Match Continuation**
- Start the next match directly from Ready to Play.
- Reuse existing match configurations.
- Generate new player matchups without returning to Match Setup.
- Preserve previous match history.
- Edit Match Setup when necessary.

### 🏆 3. Competitive Game

Designed for friendly tennis tournaments and community competitions.

**Tournament Setup**
- Singles and Doubles.
- Single Elimination and Round Robin + Knockout formats.
- Fixed Partner and Random Partner options for Doubles.
- Manual or system-generated fixed pairing.
- Player registration before generating a tournament.

**Tournament Management**
- Random Draw generation.
- Automatic BYE handling for supported knockout formats.
- Tournament brackets and match progression.
- Current Match and Next Match information.
- Automatic winner detection.
- Next Match navigation after completing a match.
- Third-place playoff for supported tournament formats.

**Individual Ranking**

For Doubles with Random Partner, players are ranked individually rather than as permanent teams.

- Win: 3 points per player.
- Loss: 0 points.
- Individual wins, losses, and win rate.
- Ranking based on accumulated results.
- Tie-breakers using Win Rate, Game Difference, and Games Won.
- Ranking-based qualification for supported tournament formats.

**Note:** Tournament progression and third-place playoff availability depend on the selected format. Random Partner Doubles uses special qualification rules and may not support every conventional bracket scenario.

### 📊 4. Live Scoreboard

- Real-time point updates.
- Automatic scoring calculations.
- Current server indicator.
- Winner announcement after match completion.
- Clear Next Match action.
- Responsive scoreboard for mobile and desktop.

### 📜 5. Match History & Data Management

- Automatic local match history.
- Completed and incomplete match records.
- Multiple matches in one session.
- Browser-based data persistence.
- Reset Tournament for tournament data.
- Reset All Data for clearing CourtScore data after confirmation.

## 🚀 How to Use

### Casual Game

1. Open CourtScore and select **Casual Game**.
2. Choose Singles or Doubles.
3. Select Fixed Partner or Random Partner for Doubles.
4. Register all available players.
5. For Fixed Partner, choose partners manually or let the system randomize them.
6. Configure the match format and scoring rules.
7. Click **Start New Match**.
8. Use **+ Point** to update the score.
9. When the match finishes, view the winner.
10. Click **Next Match** to continue with another matchup without returning to Match Setup.

New players can be added during the session through Player Management.

### Competitive Game

1. Open CourtScore and select **Competitive Game**.
2. Choose Singles or Doubles.
3. Select **Single Elimination** or **Round Robin + Knockout**.
4. For Doubles, choose Fixed Partner or Random Partner.
5. Register all participating players.
6. For Fixed Partner, manually assign teams or randomize partners once.
7. Generate the tournament draw.
8. Review the tournament bracket and upcoming matches.
9. Start the current match and record points through the scoreboard.
10. After a match finishes, review the winner and click **Next Match**.
11. Continue until the tournament reaches its final results.

### Reset Data

**Reset Tournament:** Clears the current tournament information without intentionally resetting unrelated Casual Game data.

**Reset All Data:** Clears CourtScore's locally stored application data after user confirmation.

Use Reset All Data after finishing a tennis session when previous match records are no longer needed.

## ⚙️ Scoring Rules

| Scoring Type | Rules |
|---|---|
| Regular Game | 0 → 15 → 30 → 40 → Game |
| Deuce | At 40–40, a player or team must win two consecutive points |
| No-Ad | At Deuce, the next point determines the game winner |
| Short Set | First to 4 games with a 2-game margin; tie-break at 4–4 |
| Regular Set | First to 6 games with a 2-game margin; tie-break at 6–6 |
| Tie-break | First to 7 points, win by 2 |
| Super Tie-break | First to 10 points, win by 2 |
| Best of 3 | First to win 2 sets |
| Best of 5 | First to win 3 sets |

The availability of certain scoring settings depends on the selected match format.

## 💾 Data Storage & Limitations

CourtScore uses browser LocalStorage.

- Data is stored on the device and browser being used.
- Refreshing the page does not normally remove saved data.
- Match history is not automatically synchronized across devices.
- Clearing browser storage or using Reset All Data removes saved CourtScore data.
- Data is not stored in a GitHub database.
- Tournament scoring is managed from the browser currently operating the application.

CourtScore is intended primarily for casual and friendly tennis activities.


## 🤖 AI Credits

**Created with the assistance of Artificial Intelligence (AI).**

CourtScore was developed using **ChatGPT by OpenAI** to assist with:

- UI/UX design and frontend implementation.
- Tennis scoring logic.
- Player management and pairing workflows.
- Tournament generation and ranking logic.
- Code improvements and debugging.
- Technical documentation.

The original project concept, requirements, feature decisions, and product direction came from a tennis enthusiast who wanted to make scoring and organizing tennis matches easier.

This project demonstrates how AI-assisted development can transform a simple real-world problem into a practical web application.

## ❤️ Made for Tennis Lovers

CourtScore is a personal, AI-assisted project created to help players spend less time managing scores and more time enjoying the game.

**Play more. Count less. 🎾**

---

*CourtScore — Made with ❤️ and AI for tennis lovers.*
