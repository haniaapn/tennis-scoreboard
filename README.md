# 🎾 CourtScore — Tennis Scoreboard

A simple, mobile-friendly tennis scoreboard designed to make score tracking easier, faster, and more enjoyable during tennis matches.

Built with HTML, CSS, and JavaScript, CourtScore automatically calculates tennis scores, allowing players to focus on the game instead of manually keeping track of points, games, and sets.

## 💡 Background

CourtScore was created from a simple problem: keeping track of tennis scores during casual matches can sometimes be confusing, especially when playing doubles, rotating players, or managing multiple matches in one session.

This project aims to simplify tennis scoring by providing an easy-to-use digital scoreboard that automatically calculates scores based on the selected match rules.

No registration, installation, or complicated setup is required. Just open the website and start playing!

## ✨ Features

### Match Setup
- **Singles & Doubles:** Supports 1 vs 1 and 2 vs 2 matches.
- **Flexible Match Format:** Choose between available match formats, including Standard Set and Short Set.
- **Custom Player Names:** Enter player names before starting a match.
- **Scoring Configuration:** Configure game scoring and deciding-set rules.
- **Dynamic Scoring Rules:** View match and scoring rules based on the selected configuration.
- **Default Setup:** Doubles with Short Set format.

### Live Scoreboard
- **Automatic Scoring:** Automatically calculates points, games, and sets.
- **Deuce & Advantage:** Supports traditional tennis scoring.
- **Tie-break:** Automatically handles tie-break scoring based on match configuration.
- **Live Score Updates:** Scores update instantly when a point is added.
- **Undo:** Revert the previous scoring action.
- **Restart Match:** Restart the current match without deleting previous match history.

### Match Management
- **Multiple Matches:** Start a new match with different players without clearing previous results.
- **Match History:** View previously recorded matches below the scoreboard.
- **Incomplete Matches:** Preserve an unfinished match when starting another match.
- **Local Storage:** Match data is stored automatically in the browser.
- **Reset All Data:** Clear all CourtScore match data when a tennis session is finished.

### Accessibility
- Mobile-friendly and responsive design.
- No login or registration required.
- No backend or database required.
- Free to use through GitHub Pages.

## 🚀 How to Use

### 1. Match Setup
1. Open the CourtScore website.
2. Select the Match Type: Singles or Doubles.
3. Enter the player names.
4. Select the Match Format and scoring rules.
5. Review the Match & Scoring Rules displayed below the setup form.
6. Click **Start New Match**.

### 2. Start Playing
1. The website opens the Ready to Play page.
2. Tap **+ Point** for the player or team that wins a point.
3. CourtScore automatically updates the points, games, and sets.
4. Continue until the match is completed.
5. Use **Undo** if a point was added incorrectly.

### 3. Start Another Match
1. Click **+ New Match**.
2. Configure the next match and enter new player names.
3. Click **Start New Match**.
4. Previous match history remains available below the scoreboard.

### 4. View Match History
- Scroll below the scoreboard to view recorded matches.
- Completed matches are automatically saved.
- Unfinished matches can also be recorded as incomplete.

### 5. Reset All Data
1. Click **Reset All Data**.
2. Confirm the reset action.
3. All locally stored CourtScore match data will be deleted.

**Note:** Reset All Data only clears CourtScore data, not unrelated browser data.

## 💾 Data Storage

CourtScore uses browser LocalStorage to save match information.

- Match history is stored locally on the user's device.
- Data remains available after refreshing the page.
- No personal account or cloud database is required.
- Data is not automatically synchronized between devices.
- Clearing browser site data may remove saved match history.

## 🤖 Credits

**Created with Artificial Intelligence (AI)**

CourtScore was developed with the assistance of **ChatGPT by OpenAI**, including UI design, frontend development, tennis scoring logic, and feature implementation.

The project idea, requirements, and feature direction were provided by a tennis enthusiast who wanted a simpler way to track scores during casual tennis matches.

This project demonstrates how AI can help turn a simple everyday problem into a functional web application.

## 🎯 Project Purpose

**Less time counting scores, more time enjoying tennis. 🎾**

CourtScore is a personal, AI-assisted project created to make tennis scoring more convenient, especially for casual games, friendly matches, and tennis sessions with rotating players.

---

Made with ❤️ and AI for tennis lovers.
