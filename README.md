# Multiplayer TicTacToe Game

A completely Responsive Multiplayer TicTacToe Game- Works on Android, iOS, Web & Desktop! 

## Features
- Create/Join Room
- Play Realtime
- Display Points
- Round & Game Winner
- Responsive Glow Themed UI
- Cross Platform Game

## Installation
After cloning this repository, migrate to ```flutter-multiplayer-tictactoe``` folder.

Install dependencies (Client Side)
```bash
flutter pub get
```

Install dependencies (Server Side)

```bash
cd server && npm install
```

Start the server

```bash
npm run dev
```

Configure for MacOS:
Head to macos/Runner and make sure the following keys are present in DebugProfile.entitlements and Release.entitlements
```bash
<key>com.apple.security.network.server</key>
<true/>
<key>com.apple.security.network.client</key>
<true/>
```

Run App
```bash
flutter run // After selecting the device you want to test on
```

## Usage
1. **Join or Create Game:** Enter the game lobby to either join an existing game room or create a new game room. You can invite friends or opt for random matchmaking.

2. **Place Moves:** Take turns with your opponent to place moves on the Tic-Tac-Toe board. The first player to form a line (horizontal, vertical, or diagonal) with their symbol wins the match.

3. **Chat with Opponent:** Communicate with your opponent using the integrated chat feature to discuss strategies, exchange banter, or simply enjoy the gaming experience.

4. **Review Match History:** After each match, review your match history to see detailed statistics, including wins, losses, draws, and performance metrics.

## Customization
You can customize Multiplayer Tic-Tac-Toe by modifying aspects such as the user interface design, gameplay mechanics, matchmaking algorithms, chat features, authentication methods, and overall user experience. Additionally, you can add new features, integrate with external services, or optimize performance for specific use cases.

## Tech Used
**Server**: Node.js, Express, Socket.io, Mongoose, MongoDB

**Client**: Flutter, Provider

