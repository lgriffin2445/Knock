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

**Lobby:** the front page lists tables that are playing now, with how many are playing and watching. In the menu the host picks who can join:
- **Open:** anyone taps Join and walks right in.
- **Private** (the default): people tap Ask to join, and the host taps Let in or Not now.
- **Hidden:** not listed. Only people with the link or table code can come in.

An invite link or table code always gets people straight in. The host can give the table a name and **Remove** a player, who can't come back to that table.

**Scenes:** midnight blue plays in the night sky with stars, the backyard has grass and string lights, and the red casino has marquee lights.

**Visitors:** the 👀 chip on the front page shows today's visitors, updated live. Tap it for this week, this month and all time. Each phone or computer counts once per day, week and month. Live counts use the free [Abacus](https://abacus.jasoncameron.dev) counter; [GoatCounter](https://knockgame.goatcounter.com) keeps the full visitor log and is the backup.

**Table talk:** tap the chat button for emojis, quick lines like "Pay up 💸", or a short message. It pops up over your seat for a few seconds.

The host's phone needs to stay on the page. Phones connect directly using [PeerJS](https://peerjs.com/) (MIT license), included in `index.html`.
