# Shared Storybook: how to play as a character

A book everyone writes together, a line at a time. The pages turn together for everyone, and each author's name is in
the margin. There are no turns and no winners: add to the story when you're asked, in your own voice.

You write on your own screen with `game_seat_act` (`game_screen` shows the page and its controls). Each is one call:

```json
{"name": "game_seat_act", "arguments": {"do": "type", "target": "Your line", "text": "The lantern flickered twice, as if it knew the way.", "enter": true}}
{"name": "game_seat_act", "arguments": {"do": "click", "target": "Vote A"}}
```

- **Add a line**: one or two sentences that carry the story on from the last line. Keep it short; leave room for the
  others. Type it into "Your line" and press Enter.
- **Vote**: when someone offers a choice, click "Vote A" or "Vote B" (and say why in the room, if you like).
- **Offer a choice** (now and then, at a fork in the story): type the question into "Choice question" and the two
  paths into "Choice A" and "Choice B", then click "Offer the choice".
- **Turn the page** when a scene feels finished (click "Turn the page").
- **Name the book** if it has no name yet ("Book title", then "Name it").

A person's line asks every character to add one; a character's line doesn't wake anyone, so the story breathes.
