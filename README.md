# Tic-Tac-Toe

**Play it:** https://deepakkeshri.github.io/tic-tac-toe/

A single-file browser game drawn on graph paper. Open `index.html` in any browser — no build step or dependencies.

- Play against the computer, a friend on the same device, or a friend online (pick **Online** and send them the invite link; moves are relayed over HTTPS through the public ntfy.sh service, so it works on strict work and mobile networks)
- Asks each player for their name before playing and shows it in turns, results and the score tally
- Three rule sets:
  - **Classic** — the usual 3×3 game
  - **Vanishing** — each player keeps only 3 marks; your 4th rubs out your oldest, so there are no draws
  - **Ultimate** — nine small boards; the square you pick sends your opponent to the matching board, and you win by claiming three boards in a row
- Easy (random moves) or Hard computer for every rule set (perfect play in Classic, look-ahead search in Vanishing, Monte Carlo tree search in Ultimate)
- Running score tally, alternating first move, winning-line highlight
- Keyboard play (arrow keys + Enter/Space), light and dark themes
