# Knock

A two-card game for up to 10 friends, played with play tokens. Open the site, tap **Start a table**, and share the link. Friends join from the link with just a name, and can take a seat or just watch from the audience. The person who starts the table is the **host**: their phone runs the game and hands out tokens (10.00 each to start).

- The first hand deals once everyone seated taps **I'm ready** (the host can tap **Start now**). After that, hands keep coming.
- When a new pot starts, everyone antes 0.50. The dealer gives everyone two cards only they can see.
- The player who gets cards first decides first, then it goes around the table: **Knock** or **Fold**. Who gets cards first moves one seat left every deal.
- One knocker takes the pot; the next hand starts over with antes.
- Two or more knock: the best hand takes the pot, and every knocker who loses puts up the whole pot amount (even below zero). That money is the next pot; nobody antes, and folders play it free.
- Tie for the best hand: only the tied players get two new cards each, and the higher hand wins.
- Nobody knocks: the pot stays, everyone antes again, and new cards are dealt.
- The dealer deals from one shuffled deck until there aren't enough cards for everyone to get two. Then it's reshuffled and the player to the dealer's left deals, starting with the player on their left.
- New players wait until the deck in play runs out, then sit just to the new dealer's right (last in line).
- At each deck break, everyone taps **Keep playing** or **I'm out**. Anyone who doesn't answer before the countdown ends sits out the next deck and pays nothing. You can also tap **Sit out** any time; it starts with the next hand. Sitting out keeps your seat and tokens, and **Deal me back in** puts you back the next time a fresh pot starts (everyone antes).
- Leaving doesn't get anyone out of paying: a knocker who leaves before the showdown is still in it, and if they lose they still put up the pot.
- Pairs beat everything (Aces high, down to Twos), then Ace-King, Ace-Queen and down to Three-Two. Suits don't matter.

**Extras:** cards slide out from the dealer, a big KNOCK! shakes the table, tokens slide from the pot to the winner, and tiebreak cards are dealt and flipped at the tied seats. A recap after each deck shows the biggest pot, most knocks and who's up. Pick an emoji look, tap someone's seat to throw a 🍅 at them, mute sounds in the menu, and the host can switch the room between green felt, red casino, midnight blue and a backyard wood table. Watchers get chairs in the corners. The menu has tonight's leaderboard.

## Pitty Pat

Pick **Start Pitty Pat** on the front page. 2 to 6 players, everyone starts with 20.00 and antes 0.50 into the game pot each hand.

- Fresh deck every hand. The dealer deals 5 cards each, starting on their left; the rest is the pile. The deal passes left every hand, and the player left of the dealer goes first.
- On your turn, pull a card. If it matches a card in your hand, tap **Pair it**: the pair goes down face up and you throw out any card. If it doesn't, you throw out the card you pulled.
- Every thrown card is up for grabs for 8 seconds (the host can change this). Tap **Take it** if it matches. If two people tap, the one closest to the thrower's left gets it, and play continues to their left.
- A match is the same rank. Pairs you're dealt stay hidden, and you can't take a third card for a pair you already hold. Three of a kind takes the fourth for two pairs.
- **Don't sleep:** if a thrown card matched yours and you didn't get it, your card goes dead. It's turned face up and has to be the next card you throw after you make a pair. If another card of that rank comes up, pulled or thrown, you can still match it with your dead card.
- You win when every card left in your hand is paired, with no dead cards: **Pitty Pat!** The winner takes the game pot.

### Pitty Pat side pots

The host can turn on side pots in the menu (0.25, 0.50 or 1.00 each a hand): **🎨 Colors**, **♠ Spades** and **🎯 Porter**.

- Flip the switches under your cards before the deal. A side pot rolls over until it's won. Once you're in you pay every hand to stay in; drop out and what you put in stays, and you can't rejoin until it's won and back at zero. New players can only join at zero.
- **Colors:** a same-color pair (both red or both black) in your first five cards. **Spades:** a spade in your first five cards. Claim in the 10 seconds after the deal (play waits). Only the count of claims is shown. At the end of the hand the highest Colors pair and the highest spade win; ties split; no claims means it rolls over.
- **Porter:** tap it when you're waiting on one card to go out. The first true claim wins the Porter pot right away. If nobody hits it, it rolls over.
- Nothing is claimed for you: forget to tap and you don't win it.

**Put it on your home screen:** Knock works like an app. On iPhone, open the link in Safari, tap Share (it may be under •••), then Add to Home Screen. On Android, open it in Chrome and tap Install (or ⋮ then Add to Home screen).

**Lobby:** the front page lists tables that are playing now, with how many are playing and watching. In the menu the host picks who can join:
- **Open:** anyone taps Join and walks right in.
- **Private** (the default): people tap Ask to join, and the host taps Let in or Not now.
- **Hidden:** not listed. Only people with the link or table code can come in.

An invite link or table code always gets people straight in. The host can give the table a name and **Remove** a player, who can't come back to that table.

**Scenes:** midnight blue plays in the night sky with stars, the backyard has grass and string lights, and the red casino has marquee lights.

**Visitors:** the 👀 chip on the front page shows today's visitors, updated live. Tap it for this week, this month and all time. Each phone or computer counts once per day, week and month. Live counts use the free [Abacus](https://abacus.jasoncameron.dev) counter; [GoatCounter](https://knockgame.goatcounter.com) keeps the full visitor log and is the backup.

**Big moments:** OMG BIG POT at 20.00 (MEGA at 50.00, MONSTER at 100.00) with money raining down; EVERYBODY KNOCKED when 3 or more players all knock; a tumbleweed when nobody knocks; STOLE IT when one knocker takes the pot alone; OUCH when a pair loses; ON FIRE after 3 pots in a row; lights dim with a drumroll before a tiebreak; and your own cards glow when you're dealt a pair (only you see that one).

**Table talk:** tap the chat button for emojis, quick lines like "Pay up 💸", or a short message. It pops up over your seat for a few seconds.

The host's phone needs to stay on the page. Phones connect directly using [PeerJS](https://peerjs.com/) (MIT license), included in `index.html`.
