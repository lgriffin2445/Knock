# Knock

A two-card game for up to 10 friends, played with play tokens. Open the site, tap **Start a table**, and share the link. Friends join from the link with just a name.

- Everyone antes 0.50 each hand and gets two cards only they can see.
- Going around the table, each player chooses **Knock** or **Fold**.
- One knocker takes the pot. With two or more, the best hand takes it and every knocker who loses pays the whole pot into the next pot.
- Nobody knocks: the pot rolls over. Ties split.
- Pairs beat everything (Aces high, down to Twos), then Ace-King, Ace-Queen and down to Three-Two. Suits don't matter.

The dealer's phone runs the table, so it needs to stay on the page. Phones connect directly using [PeerJS](https://peerjs.com/) (MIT license), included in `index.html`.
