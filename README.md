# Kahallum

A family games app with two games: make-your-own quizzes, and Draw & Guess. Both are played together in the same room.

Everything is in one file: `index.html`. Open it in any web browser. No install, no accounts.

## Making a game

1. Tap **Make a new game**.
2. Give it a name and a cover picture.
3. Add questions. Each one can have a picture, 2 to 4 answers, and a timer (10, 20, 30 or 60 seconds).
4. Tap the ✓ next to the right answer (you can tick more than one).
5. Tap **Save and play**.

There's also a **true or false** question button for quick ones.

## Question packs

There are 15 packs of ready-made questions for about age 8, with 32 questions in each: Animals, Maths, Space, Technology, Science, Minecraft, Zelda, Fortnite, Padel, Dinosaurs, Football, Human Body, Food, Around the World and Pokémon.

- **Quick play**: open a pack and tap **Quick play** for 10 random questions.
- **Make your own**: tap questions to pick them (or **Pick 10 at random**), then **Make a game**. You can change any question afterwards.
- **Mix packs**: in the game editor, tap **Add from a question pack** as many times as you like.

The questions live in the `PACKS` list near the bottom of `index.html`, so it's easy to add more.

## Playing

Add everyone who's playing (Kahallum remembers them for next time), then pick a way to play:

- **📺 Quizmaster**: put it on a TV or laptop. The question and four coloured answers show up with a countdown. Everyone shouts or points at their answer. Then the quizmaster shows the answer and taps who got it right, in the order they answered. First right answer gets 1000 points, the next 900, and so on.
- **📱 Pass the phone**: everyone takes a secret turn on the same phone or tablet. Faster right answers score more (500 to 1000 points).

Getting several right in a row builds a 🔥 streak worth bonus points. The winner gets a podium and confetti.

## Draw & Guess

A pass-the-tablet drawing game. Pick who's playing, which categories to draw from (16 categories, over 500 things to draw), how many rounds, and how long each drawing gets (45, 60 or 90 seconds). Everyone draws once per round.

1. The tablet is passed to the artist, who secretly sees their word (they can swap it up to twice).
2. They draw it with pens, a fill bucket, a rubber, undo and clear. Everyone else watches and shouts out guesses. The category is shown as a hint.
3. When someone gets it, the artist taps **Someone guessed it!** and picks who. The guesser scores 50 to 100 points (faster is more) and the artist gets 50.

Every drawing is saved to the **Gallery** on that device (the newest 60), with the word, who drew it and who guessed it. Pictures can be saved as image files from there.

The words live in the `DRAW_CATS` list in `index.html`.

## Sharing a quiz with another device

Tap **Share** on a game to get a code that starts with `KAHALLUM:`. Copy it and text or email it to another phone. On that phone, open Kahallum, tap **Add a shared game**, and paste the code.

## Where games are saved

Games are saved in the browser on the device you made them on. If you clear the browser's data, they're gone, so share a code to yourself as a backup for games you love.

When Kahallum is opened as a Claude artifact, games are also saved to your account, so they show up on every device you open that link on.

## Putting it online

To get a link the whole family can open, turn on GitHub Pages for this repo (Settings → Pages → deploy from the branch, root folder). The game will then be at `https://<your-username>.github.io/kahallum/`.
