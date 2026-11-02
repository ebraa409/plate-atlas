# Plate Atlas

A food guessing game. You see a dish's photo, description and ingredients, and guess which country it comes from. You get five guesses. After two wrong guesses the dish's name is revealed. Each guess shows how close you are (Hot, Warm, Cool, Cold, Freezing) and an arrow pointing toward the answer.

## Where the dishes come from

- **95 hand-written dishes** with clues written to avoid naming the country.
- **A few hundred more pulled live from Wikipedia's [National dish](https://en.wikipedia.org/wiki/National_dish) article** each time the page loads. Their description comes from the dish's Wikipedia summary, with country names, nationalities and well-known regions hidden.
- **All photos load live** from Wikipedia while you play. Nothing is stored in this repo.

Everything runs in the browser. There's no server and no build step: it's one `index.html`.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Photos and dish text: Wikipedia contributors, under CC BY-SA and the licenses listed on each image's page.
