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
- Pairs beat everything (Aces high, down to Twos), then Ace-King, Ace-Queen and down to Three-Two. Suits don't matter.

**Extras:** cards slide out from the dealer, a big KNOCK! shakes the table, tokens slide from the pot to the winner, and tiebreak cards are dealt and flipped at the tied seats. A recap after each deck shows the biggest pot, most knocks and who's up. Pick an emoji look, tap someone's seat to throw a 🍅 at them, mute sounds in the menu, and the host can switch the room between green felt, red casino, midnight blue and a backyard wood table. Watchers get chairs in the corners. The menu has tonight's leaderboard.

**Table talk:** tap the chat button for emojis, quick lines like "Pay up 💸", or a short message. It pops up over your seat for a few seconds.

The host's phone needs to stay on the page. Phones connect directly using [PeerJS](https://peerjs.com/) (MIT license), included in `index.html`.
