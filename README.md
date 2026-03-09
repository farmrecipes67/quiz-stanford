# 🎓 Stanford Insider Quiz

![Stanford Campus](https://drive.google.com/uc?export=view&id=1JeYrddKaqIO-mFCyank2rlEGMFDUuffJ)

## About This Quiz

Think you know Stanford? This insider quiz tests your knowledge of campus traditions, history, famous alumni, hidden gems, and little-known facts that only true insiders would know.

**10 questions • 5 choices each • How well do you really know Stanford?**

## How to Use

### Questions
Check out [`questions.js`](./questions.js) for the full quiz with all 10 questions and their multiple-choice options.

### Answers
The answer key with explanations is in [`answers.js`](./answers.js) — no peeking until you're done! 👀

## Quick Start

```javascript
const { questions } = require('./questions');
const { answers } = require('./answers');

// Display a question
console.log(questions[0].question);
Object.entries(questions[0].choices).forEach(([key, val]) => {
  console.log(`  ${key}: ${val}`);
});

// Check answer
console.log(`Correct: ${answers[0].correct} - ${answers[0].explanation}`);
```

## Sample Question

> **At Full Moon on the Quad, what item has traditionally been handed out before the midnight countdown?**
> - **A.** Glow sticks
> - **B.** Red roses
> - **C.** Plastic leis
> - **D.** Stanford Axe stickers
> - **E.** Chocolate coins

<details>
<summary>🔍 Click to reveal answer</summary>

**B** — Roses were a staple giveaway at FMOQ before the midnight kiss.

</details>

## Quiz Topics Covered

- 🏛️ Campus traditions & rituals
- 📜 University history & founding stories
- 🌟 Famous alumni & their connections
- 🗺️ Hidden spots & insider knowledge
- 🎯 Little-known facts & surprising trivia

---

<div align="center">

*Generated with 💜 by [Papersaurus](https://github.com/farmrecipes67) 🦕*

*Quiz content created using AI • Campus image generated with AI*

</div>

<!-- Open Graph Tags for Social Sharing -->
<!-- og:title: Stanford Insider Quiz -->
<!-- og:description: Think you know Stanford? Take this 10-question insider quiz covering campus traditions, history, famous alumni, and little-known facts! -->
<!-- og:image: https://drive.google.com/uc?export=view&id=1JeYrddKaqIO-mFCyank2rlEGMFDUuffJ -->
<!-- og:type: website -->
