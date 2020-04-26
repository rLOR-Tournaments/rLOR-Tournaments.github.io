# Season Tourney Rules & Procedure

## Sign-ups

The scheduled **Tournament Start** time for season tourneys is currently:
- `@EU Tournaments`: Sundays @ 7:00 PM BST/GMT [London time]
- `@AM Tournaments`: Sundays @ 6:00 PM EDT/EST [New York time]

There are three parts to joining each tournament:
- **Sign-ups**: `@Bannerman` posts sign-ups in `#event-news` **120 minutes** before Tournament Start and closes sign-ups **45 minutes** before Tournament Start. React to this post with the designated checkmark during this time to enter and sign-up, gaining an `@EU Tourney Participant` role or `@AM Tourney Participant` role and visibility of hidden tournament channels. Remove the reaction to leave.
- **Registration**: After signing-up, `@Bannerman` will send a DM to start an interactive registration. Follow its instructions to register in-game name and deck lists. Registration ends **30 minutes** before Tournament Start, so complete registration with the `register` command before then.
- **Check-in**: Check-in starts **60 minutes** before Tournament Start and ends **15 minutes** before Tournament Start. Post (anything) to the `#check-in` channel (hidden before entering) to check-in.

Season tourneys are capped at **64 players**. Any number of members can sign-up and register, but priority is given to players in registration completion order. Leaving the tourney removes a player from the queue, and re-entering places the player at end of the current queue. Any players beyond 64th in the queue are on standby, and move up in the queue whenever another player leaves the tourney.

At any time between the end of Check-in and the scheduled Tournament Start, the TO will:
1. Post public player info, including deck lists if the tourney is open-list. Players should double-check their info for accuracy.
2. Post the first-stage bracket with finalized Round 1 matches.
3. Announce the start of Round 1.

## Brackets

Each season tourney is a two-stage tournament:
1. A **Swiss bracket** lasting exactly **4 rounds**.
2. An **adaptive single-elimination top cut** lasting **0-2 rounds** (given a player cap of 64 players).

The Swiss bracket is seeded using results from the **previous 6 season tourneys**, including tourneys from the season prior. The formula is `(MatchesWon + 8) / (MatchesPlayed + 16)`, with ties broken randomly.

Each round's match pairings are generated using Challonge (brackets hosted in [the rLOR Challonge community](https://challonge.com/communities/rlor)). After 4 rounds, the first-stage ranking is determined using the default Challonge method, which is Match Score followed by four tiebreakers in this order:
0. **Match Score** (1 point for each match win and bye; 0.5 points for each match draw)
1. **Match Tiebreaker** (match wins against players with the same Match Score)
2. **Median-Bucholz** (the sum all all opponents' Match Scores, with largest and smallest discarded)
3. **Game Differential** (the difference between game wins and losses)
4. **Initial Seeding**, low seed ranking higher

After 4 rounds of Swiss, the tourney needs a second stage if there are multiple players with a Match Score of 4.0 (e.g. a 4-0 record or a 3-0 record with a bye). The result for each number of players with Match Score 4:
- **0 players**: No second stage. The highest-ranked player wins.
- **1 player**: No second stage. The single player with Match Score 4 wins.
- **2 players**: Top cut of 2. Both players with Match Score 4 fill the bracket.
- **3 players**: Top cut of 4. All players with Match Score 4 *and* the next-highest-ranked player fill the bracket.
- **4 players**: Top cut of 4. All players with Match Score 4 fill the bracket.

The second-stage bracket is reseeded by first-stage ranking.

## Rounds

The TO will announce the **Round Start** of each new round. After this announcement, each player must check-in by posting (anything) to the `#check-in` channel as soon as possible.

- There are no penalties for checking-in in the **10 minutes** after Round Start.
- At each **10-minute interval** after Round Start, if Player A in a match has checked in but Player B hasn't, then Player B forfeits a game.
- When Player B forfeits a game in this manner, Player A's win total increments by 1. However, the game counter does *not* increment by 1. *Example*: Player A checks-in after 2 minutes and Player B checks-in after 14 minutes. A & B's first game is Game 1, and Player A's game record starts at 1-0.
- At each **20-minute interval** after Round Start, if neither Player A nor Player B in a match have checked-in, then the tournament reduces by 1 the number of wins needed by either player to win the match.
- If this reduces the number of such wins to 0, then the match ends in a 0-0 draw.

All season tourney formats use Best-of-3 (Bo3) matches with the following rules. Casual tourney formats will generally follow these rules, but may differ on a tourney-by-tourney basis and may use non-Bo3 formats.

- A match ends at the point reached first:
  - The match reaches 3 games played (Game 1, Game 2, and Game 3).
  - A player reaches 2 games won (by `VICTORY` or by forfeit).
  - The TO ends the match (by itself or as part of the round).
- A `TIE GAME` (e.g. at Start of Round, both players are at 1 life and draw a Poison Puffcap) counts as a game played and increments the game counter, but doesn't count as a [whole or partial] win or loss for either player.
- If a player enters a game with an illegal deck, they lose that game. This deck can be either a deck not in their registered lineup or a deck in their lineup that the match format prevents them from using that particular game.
- If a player disconnects while in-game and can't reconnect, they lose that game. Disconnects within the lobby are not a loss for either player unless a frequent occurrence for a particular player.
- If the TO ends an ongoing match, it ends in either a 1-1 draw if both players won a game or a 0-0 draw elsewise.

At the end of each match, both players must report the result of the match to `#match-results`. A match result is generally accepted in any of these forms:
- Either player posts a *screenshot* of the lobby that shows the final score.
- Both players report the same result.
- The losing player reports a score of 2-0.

All players should snap screenshots of the lobby score to be safe. In the case of lobby issues forcing multiple lobbies for a match, both players should report the final result.

The TO has flexibility on when to start and end Bo3 rounds, but will follow these guidelines:
- The TO won't post Round Start earlier than **50 minutes** before the previous Round Start. They can post Round Start at any time afterward (as soon as possible).
- If any matches are ongoing **60 minutes** after Round Start, the TO can end the round at any time by their discretion. At Round End, players must stop all ongoing games.
- *Player communication is important!* Players in ongoing games should contact the TO with an update before 60 minutes have passed, or run the risk of sudden Round End after 60 minutes.
