# Knock

A two-card game for up to 10 friends, played with play tokens. Open the site, tap **Start a table**, and share the link. Friends join from the link with just a name. The person who starts the table is the **host**: their phone runs the game and hands out tokens (10.00 each to start).

- When a new pot starts, everyone antes 0.50. The dealer gives everyone two cards only they can see.
- The player who gets cards first decides first, then it goes around the table: **Knock** or **Fold**. Who gets cards first moves one seat left every deal.
- One knocker takes the pot; the next hand starts over with antes.
- Two or more knock: the best hand takes the pot, and every knocker who loses puts up the whole pot amount (even below zero). That money is the next pot; nobody antes, and folders play it free.
- Tie for the best hand: only the tied players get two new cards each, and the higher hand wins.
- Nobody knocks: the pot stays, everyone antes again, and new cards are dealt.
- The dealer deals from one shuffled deck until there aren't enough cards for everyone to get two. Then it's reshuffled and the player to the dealer's left deals, starting with the player on their left.
- Pairs beat everything (Aces high, down to Twos), then Ace-King, Ace-Queen and down to Three-Two. Suits don't matter.

**Table talk:** tap the chat button for emojis, quick lines like "Pay up 💸", or a short message. It pops up over your seat for a few seconds.

The host's phone needs to stay on the page. Phones connect directly using [PeerJS](https://peerjs.com/) (MIT license), included in `index.html`.
