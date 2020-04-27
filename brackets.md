# Tournament Brackets

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

**» [Tournament Rounds](rounds)**
