# Landless MTG
Version 1.1.

Landless MTG is a style of [Magic: The Gathering](http://magic.wizards.com/),
in which the deck contains no land cards.
Instead any card can be played as a land. Any card can also be played normally.
The phrases 'play as land' and 'play normally' are used below to indicate these
two modes of playing a card.

The advantages of Landless MTG are that it allows having more colors in the
deck and greater diversity of strategies.
It reduces the probability of mana starvation and spell starvation that produce
trivial games where the opponents kill the starved one.
Landless MTG also makes playing with a randomized deck possible, which allows
novel styles of play such as random draft or single deck MTG (see below).
Finally it allows more diversity of strategies from the same deck depending on
which cards are played as land and which cards are played normally.

## Rules

[Normal magic rules](http://magic.wizards.com/en/gameinfo/gameplay/formats/comprehensiverules)
are used with the following modifications:

1. Any card can be played as land or normally. When the card is played as land
   it acquires a new identity and keeps it until it moves to any zone other
than battlefield or exile.

2. If a card of one color is played as a land, it becomes the basic land of
   that color.

3. If a card of two or three colors is played as a land, it becomes a non-basic
   land that produces mana of any of its colors.  It enters the battlefield
tapped.

4. If a card of of four or five colors is played as a land, it becomes a
   non-basic land called "Transguild Promenade" with the following text:

   > Transguild Promenade enters the battlefield tapped.

   > When Transguild Promenade enters the battlefield, sacrifice it unless you pay {1}.

   > {T}: Add one mana of any color to your mana pool.

5. If a colorless card is played as a land, it becomes non-basic land called
   "Shimmering Grotto" with the following text:

   > {T}: Add {1} to your mana pool.

   > {1}, {T}: Add one mana of any color to your mana pool.

## Variations

Landless MTG enables some variations that don't work with normal rules but
become playable when you don't need to worry about the mana base of your deck
(which is normally not an issue in landless).

### Random draft

Players draft their decks randomly from a sufficiently large collection of cards.
They can play directly with the drafted deck or put part of the cards into a
sideboard and play with the rest (i.e. draft 60, build a deck of minimum 40).

### Single deck

Single deck is a game where all players draw cards from a large shared deck.
It's a simple format for fast casual play
(as there's no individual deck building at all)
that nevertheless allows a lot of diversity through the design
of the common deck (see below).

Landless rules are used with the following modifications:

1. All players share the deck for all purposes.

2. If the deck runs out, all graveyards are shuffled together to form new deck and
   the game continues.

3. The first 7 cards are dealt by one player to each player in a round-robin
   fashion.

### Single deck with double draw

Double draw is a modification of single deck game where players have limited amount
of deck building that is intertwined with the game itself.

Single deck rules are used with the following modifications:

1. At the start of the game each player is dealt 14 cards
   (round-robin, 2 cards at a time).
   The player keeps any 7 of them and
   puts the rest at the bottom of the deck in any order.
   The order in which players put cards at the bottom of the deck is the same
   as the order of turns.

2. If a player decides to mulligan, the player is dealt 12 cards, keeps 6 and
   puts the rest at the bottom of the deck.
   For each subsequent mulligan the player is dealt 2 fewer cards
   than in the previous mulligan, keeps half of them and
   puts the rest at the bottom of the deck.

   a. There’s no Scry 1 for players that ended up with fewer than 7 cards.
      The reasoning is that they are adequately compensated
      by having more information about the cards at the bottom of the deck.

3. During the game, when the rules or a card make a player draw N cards,
   the player takes 2xN cards from the deck,
   picks N of them and puts the remaining N at the bottom of the deck in any order.

## Deck design for single deck and random draft

In principle any assortment of cards could be used for single deck or random draft.
Not all of them would be equivalently balanced and interesting.

In order to make the game more predictable it could be useful to balance out the
colors and rarities of the cards. It seems (although I haven't checked this) that
having the same number of cards of each color and roughly the same number of
colorless cards would work.

Rarity distribution would also have an effect on the game with
complexity of the game rising as the percentage of rarer cards is increased.
For a feel close to normal booster draft we could use
the same distribution as in booster packs.
From brief research it appears to be 80 commons
to 24 uncommons to 7 rares to 1 mythical rare.

For 2-8 players a deck of 200 cards composed of non-land cards
according to the following table can be used:

|               | Colorless | One color | Two colors | TOTAL |
|---------------|----------:|----------:|-----------:|------:|
| Mythical rare |         2 |           |            |    2  |
| Rare          |         4 |        2  |            |   14  |
| Uncommon      |         7 |        7  |            |   42  |
| Common        |        17 |       17  |         4  |  142  |
| TOTAL         |        30 |       26  |         4  |  200  |

There are five colors and ten pairs of colors,
so for example for commons we will have
17 colorless, 17x5=85 cards of one color and 4x10=40 cards of two colors
for a total of 142 common cards.

For smaller games it should be possible to build a deck or around 100 cards
with roughly the same proportions.

It is usually not desirable to include very few very powerful cards into a
randomized deck because any player who draws one of those cards would have a
big advantage. This increases the role of chance and decreases the role of
skill.

----------------------------------------

The content of this document is available under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Magic: The Gathering content and materials are trademarks and copyrights
of Wizards of the Coast its licensors. All rights reserved.
