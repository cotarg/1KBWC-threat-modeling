# Congenial Carnival Rule Sheet (1kBWC)
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

To prepare the cards, look at the system laying on the table and brainstorm 3 (three) vulnerabilities, and 3 (three) security measures that apply to the system. Fill the cards in your hand with these brainstormed aspects. There will almost certainly be duplicates and that is OK!

### Gameplay:

#### Basic turn order:
1: Play one card.
2: Do any actions required by the card or cards on the table.
3: Pull one card from the deck in play.

#### Playing a Card: 
On your turn you will take a card from your hand and lay it on the table. If you are playing a blank card, part of the process of play is writing on your card. If you’re playing a pre-prepared card, you will lay the card on the table in the play area.

When you place your card on the table, ask if anyone else holds a matching card. Use your discretion here. If your system is in need of a firewall, and someone posts “open port 22”, accept “open port” as a duplicate no matter the port specified. If your system is a girl scout troupe, and the card someone plays is “sold out of cookies”, accept “sold out of thin mints”. However, if someone plays “sold out of thin mints”, then “sold out of caramel delites” and “sold out of all cookies” would not be duplicates.

Each player who has a duplicate may receive a replacement blank card from the replenishment deck _if they wish_. If so, they may prepare this card whenever they want to.

#### Do any actions required by the previously played cards:
Cards played by other players may contain actions, and if they do, you do those actions as part of your turn. See the [examples](examples) for some ideas of what this could look like.

#### Draw one card: 
There will also be a deck of cards on the table, and at the end of your turn you take one card from the deck. If the card you draw is blank you may fill it in with either a vulnerability or a security measure at your leisure. You may hang onto it as a blank until you are inspired to fill it in.
