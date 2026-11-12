# Knock

A two-card game for up to 10 friends, played with play tokens. Open the site, tap **Start a table**, and share the link. Friends join from the link with just a name.

- When the pot is empty, everyone antes 0.50. Everyone gets two cards only they can see.
- Going around the table, each player chooses **Knock** or **Fold**.
- One knocker takes the pot, and the next hand starts over with antes.
- Two or more knock: the best hand takes the pot, and every knocker who loses pays the whole pot amount. That money is the next pot; nobody antes, and folders play it free.
- Nobody knocks: the same pot stays and the cards are dealt again. Ties split the pot and the next hand starts over.
- Pairs beat everything (Aces high, down to Twos), then Ace-King, Ace-Queen and down to Three-Two. Suits don't matter.

The dealer's phone runs the table, so it needs to stay on the page. Phones connect directly using [PeerJS](https://peerjs.com/) (MIT license), included in `index.html`.
