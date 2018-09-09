# 1KBWC of Threat Modelling Rule Sheet
## Materials:
* Blank Cards — at least 25 (twenty-five) per person playing
* System Cards — Cards representing the system you are threat modeling
* Pre-made cards — cards from previous iterations of the system if you have them/want to use them
* Pens/Pencils/Crayons — at least one per person, but if you want to do art, more works
* People who want to threat model a system

## Summary:
_1KBWC of Threat Modeling_ is a card game where the cards are designed by the players. It’s a remix of the game _1000 Blank White Cards_ and _Fluxx_. The object of the game is to start with a basic concept of a system, and use creative thinking to find places the system is vulnerable and strategies to repair or mitigate the vulnerabilities. This is a semi-cooperative game, since the goal is to make a system stronger. It can be played by groups of up to 10 (ten), although 5 (five) is easier to manage as an exercise. Less than 3 (three), while lovely, is probably not going to be terribly productive, however, due to the nature of the game.

## Prior to play:
### Preparing the deck and table:
If you’ve played _1KBWC of Threat Modeling_ before, take any pre-made cards you wish to include in your current session, count them, and then bring your deck of cards up to 20 (twenty) per player by adding blank cards. If you’ve never modeled this system before, just put 20 (twenty) blank cards per player into a stack.

You will also need to maintain a reserve of blank cards, set those aside in a place where they won’t be confused for the “draw” deck, but where folks can find them if they need them. (See [templates](https://github.com/cotarg/congenial-carnival/tree/main/templates) for a few sample table layouts.)

In the original _1000 Blank White Cards_ the game begins with an empty table. In this remix, however, after preparing a deck, you prepare the table for the game by laying cards which have been prepared to model the system you’re threat modeling. Our [examples](https://github.com/cotarg/congenial-carnival/tree/main/examples) folder has a few sample systems to demonstrate what these should look like. The goal is to provide an accurate representation of the system as it currently exists, or is designed.

(If you think of ways the system is vulnerable during this step, do not mitigate them. Make a note for yourself and see if it comes up during the game, or if you can introduce it as a player.)

### Player preparation:
Give each player 6 (six) blank cards and a pen. Take ten minutes for each player to prepare the cards they want to have in their opening hands.

To prepare the cards, look at the system laying on the table and brainstorm 3 (three) vulnerabilities, and 3 (three) security measures that apply to the system. Fill the cards in your hand with these brainstormed aspects. There will almost certainly be duplicate ideas/cards amongst the players and that is OK!

### Gameplay:
Pick someone to start by whatever method you choose. (We suggest using whoever has the nearest birthday if you’re stumped for a method.) Game play will begin with them and pass around the table to the right.

#### Basic turn order:
* Play one card.
* Do any actions required by the card or cards on the table.
* Pull one card from the deck in play.

[Note: Cards in play _can_ change the turn order or add steps, though this is considered an “advanced” modification of the game.]

#### Playing one card: 
On your turn you will take a card from your hand and lay it on the table.

When you place your card on the table, ask if anyone else holds a matching card. Use your discretion here. If your system is in need of a firewall, and someone posts “open ports” or “no firewall”, accept “open port 22” as a duplicate. If your system is a girl scout troupe, and the card someone plays is “sold out of cookies”, accept “sold out of the mint cookies”. However, if someone plays “sold out of the mint cookies”, then “sold out of caramel cookies” and “sold out of all cookies” would not be duplicates. All matching (duplicate) cards should be played at this time.

Each player who has a duplicate receives a new blank card from the replenishment deck, and they may hold it to prepare when they wish. 

#### Do any actions required by the previously played cards:
Cards played by other players may contain actions, and if they do, you do those actions as part of your turn. See the [examples](https://github.com/cotarg/congenial-carnival/tree/main/examples) for some ideas of what this could look like.

#### Draw one card: 
There will also be a deck of cards on the table, and at the end of your turn you take one card from the deck. If the card you draw is blank you may fill it in with either a vulnerability or a security measure at your leisure. You may hang onto it as a blank until you are inspired to fill it in.

### Finishing the Game
#### There are three ways to end game play:
* **There are no more cards to pull into player hands.**
If the play deck is emptied, each player gets one final turn, and then the game is over.

* **The group consensus is that the game has no more useful avenues to explore at this time.**
Each player is still offered the opportunity to take a final turn if they wish.

* **The game hits the limit of its timebox.**
While leaving gameplay open-ended can be helpful, sometimes exercises like this benefit from constraints. One of the most common constraints is to introduce a time limit. If this constraint is used, at the time limit, game play ceases, regardless of if all players have finished the turn they’re on.

#### Post-game debrief:
After game play has finished, a 15 (fifteen) minute debrief period occurs. During this period, note down all the vulnerabilities uncovered and strategies for repair or mitigation. Then ask each player to contribute one thing they learned during game play to the debrief document where you’ve captured this information. If players wish to have a copy of the debrief document, make copies at this time.

#### Retaining cards:
Lastly, decide if you want to retain the cards completed during play. If you want to model this system again in the future, it can be helpful to have past cards (especially if you change your system in response to game play). You may also want to keep the cards because something interesting emerged during play, because you want to run the game for others modeling this system and will use the created cards to jumpstart it, or just because you feel like it.
