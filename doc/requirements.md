# Table Requirements
* Let there be a table at which the players can arrive at.
* Allow 4 players to participate in a game.
* Allow 6 players to participate in a game.
* Allow 8 players to participate in a game.
* Allow players to select spots at the table

# Game requirements

## Dealer Selection Requirements
* At the outset, before the first dealing, any player should be able to become the dealer of cards.

## "Thurf" Declaration Requirements
### Simple game
* All the players should be allowed to declare that they have a game, 'thurf'.
* When multiple players arbitrate for declaring the exact 'thurf' suit, the precedence order for declaration is clockwise starting from the dealer.
* After declaring a game, but before calling out the "thurf" suit by following the rules of precedence, a player should be allowed to back out his declaration
* Only one player should finally get to declar the "thurf" suit for that game
* The player that has declared the "thurf" suit should be shown in a different color.
### Game with "addu"
* WIP: Phase 2

## Game Play Requirements
### Basic gameplay (irrespective of suit)
* The game must start from the person to the right of the dealer and proceed counter-clockwise.
* Once a "pattu" goes to a player, the next round of play must proceed from that player.
* The game should end once all the player's cards are played.
### Non-thurf round 
* If a player has a thurf card during a non-thurf round, he should be allowed to play a thurf card anytime he chooses to except when a thurf card higher in rank has already been played.
* If a player has no thurf card during a non-thurf round, he should be allowed to play only non-thurf cards from that suit if he has cards from that suit. If he doesn't have cards of the suit of the round, he is free to play any card.
### Thurf round
* If the round has started with a thurf card, every other player should only be allowed to play a thurf card except when the player does not have a thurf card in which case he may be allowed to play any card in that round.
* [48 card variant]: If the person who declared thurf does not have a J, the "J" that gets last thrown onto the table should get the pattu.

## Game Scoring Requirements
* The game must keep track of how many more games a player must deal before the dealer switches to the other team
* For the non-"thurf" suit, A should be counted as 11 pts "ookulu", K as 3, Q as 2, J as 1, 10 as 10, and 9 as 0
* For the "thurf" suit, A should be counted as 11 pts "ookulu", K as 3, Q as 2, J as 20, 10 as 10, and 9 as 14
* If 24 cards are being used, the team not declaring the "thurf" suit wins if they get more than 47 points.
* If 48 cards are being used, the team not declaring the "thurf" suit wins if they get more than 94 points.

## Scoreboard requirements
### Basic requirements
* The players must be given an option to play without the app's scoreboard and use a manual scoreboard.
* The scoreboard should reflect the new score once the game ends and should show how the current score is changing after the game has ended.
* The scoreboard should show which team is currently dealing.
* The scoreboard should show how many more games are to be dealt by the team dealing currently.
### Score adjustments
#### 4 players
1. If the team dealing wins, the pending games to be dealt should be reduced by 4 games if the player dealing declared thurf
2. If the team dealing wins, the pending games to be dealt should be reduced by 2 games if player opposite to the dealer (the teammate) declared thurf.
3. If the team dealing loses, the pending games to be dealt should be incremented by 3 games
#### 6 players
1. If the team dealing wins, the pending games to be dealt should be reduced by 6 games if the player dealing declared thurf
2. If the team dealing wins, the pending games to be dealt should be reduced by 4 games if any of the other two playesr in the team (the teammate) declared thurf.
3. If the team dealing loses, the pending games to be dealt should be incremented by 5 games if the player who declared thurf is immediately next (either side) to the dealer.
4. If the team dealing loses, the pending games to be dealt should be incremented by 3 games if the player who declared thurf is dimatrically opposite to the dealer.

# Card Requirements
A, J, K, Q, 10, 9 from each suit (diamonds, hearts, clubs, spades) are the only cards to be dealt.
If one pack of cards are being used, then the card cound is 24. If two packs of cards are being used, then the card count is 48 cards.

## Card Precdence Requirements
* The precedence among cards within the thurf-suit shoule be as follows - J, 9, A, K, Q, 10
* The precedence among cards within the non-thurf suit should be as follows - A, K, Q, J, 10, 9

## Card Dealing requirements
Ensure that the cards are shuffled (randomized) and given to players
### 24 card variant
* 4 cards each are to be dealt to each player first
* 2 cards each are to be dealt to each player after "thurf" has been declared by the player.
### 48 card variant
* 6 cards each are to be dealt to each player first
* 2 cards each are to be dealt to each player after "thurf" has been declared by the player.

## Card-confidentiality Requirements
* A player should only be allowed to see his cards and no-one else's.
* A player should be able to see closed cards of other players with the current count.
* Once a team gets a 'pattu', any member of that team can see the cards of the 'pattu' later on.

# Chatbox Requirements
* A chatbox must exist for all players to chat
* The name of the player must reflect in the chat against the message he sends
* All messages in the chatbox should be visible to every other player at the table.

# Language requirements
* WIP: Where possible let there be telugu words used in telugu font. 

# "Kotu" requirements
* WIP: Phase 2