
# little joys. 💌

> A kind word or a little laugh, signed and sealed for you.

**little joys.** is a cheerful, postcard-inspired compliment and joke generator designed to brighten everyday moments. It combines thoughtful encouragement, family-friendly humor, and playful interactions in a lightweight, responsive web application.

## Features

- **100 unique compliments** across four categories: Motivation, Friendship, Kindness, and Confidence.
- **50 family-friendly jokes**, including puns, one-liners, and setup-and-punchline jokes.
- **Category filtering** to find the right kind of encouragement, or select All for a surprise.
- **Random selection without replacement** within each active content pool, with automatic replenishment when exhausted.
- **Delayed punchlines** that appear after 2.5 seconds, with a gentle reveal animation.
- **Copy to clipboard** to share compliments and complete jokes, with a manual-copy fallback.
- **Postcard-inspired design** with pastel gradients, layered paper, illustrated SVG stamps, and category-specific colors.
- **Playful micro-interactions** including lifting buttons and hover sparkles, while keeping the postcard layout stable.
- **Responsive and accessibility-conscious design** with keyboard controls, visible focus indicators, screen-reader announcements, and reduced-motion support.

## Compliment Categories

| Category | Theme | Compliments |
| --- | --- | ---: |
| Motivation | Progress, curiosity, and perseverance | 25 |
| Friendship | Connection and everyday companionship | 25 |
| Kindness | Thoughtfulness and caring for others | 25 |
| Confidence | Individuality, courage, and self-expression | 25 |

## Built With

- **HTML5** — semantic page structure and accessible controls.
- **CSS3** — responsive layout, gradients, animations, custom properties, and media queries.
- **Vanilla JavaScript** — content selection, DOM updates, timed reveals, and clipboard interactions.
- **Inline SVG** — decorative stamps, icons, and illustrations.

No frameworks, external libraries, APIs, backend, or build tools are required. All content is stored locally in JavaScript.

## Getting Started

1. Download or clone the repository.
2. Open `index.html` in a modern web browser.
3. Choose a compliment category and select **Another Compliment**, or select **Tell Me a Joke**.
4. Use **Copy** to share your favorite message.

## Project Structure

```text
little-joys/
├── index.html      # HTML, CSS, JavaScript, and content collections
├── favicon.png     # Website favicon
└── README.md       # Project documentation
```

## How It Works

Compliments are stored in a JavaScript object organized by category. Jokes are stored in an array, with each entry containing either a one-liner or a setup and punchline.

The application draws randomly from temporary content pools, removing each selected item until its pool needs to be replenished. When a new message appears, the postcard's category, colors, and stamp illustration update to match.

Two-part jokes reveal their punchline after a short pause. Generating another message cancels any pending reveal, and copying a joke always includes its full text.

## Project Goals

- Create a small, enjoyable experience that spreads positivity and laughter.
- Demonstrate practical front-end development using only HTML, CSS, and JavaScript.
- Explore responsive design, accessible interactions, and creative visual details without unnecessary dependencies.


---

*Made to make you smile ♡*
