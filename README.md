# GameFrame

Website for GameFrame — a custom sports graphics service for young athletes.
Customers send a photo, get back a professional-quality sports card, poster,
or LED sign design in 3–5 days.

## Stack

HTML5 · Tailwind CSS (CDN with custom config) · JavaScript (vanilla) · Inter (Google Fonts)

## Running it

Open `index.html` in a browser or use Live Server in VS Code.

## Pages

- `index.html` — Landing page
- `portfolio.html` — Full portfolio gallery

## Landing page sections

- **Hero** — headline, CTA buttons, hero image, trust indicators
  (3–5 day turnaround, satisfaction guarantee)
- **How It Works** — three-step flow (upload photo → design → receive files)
- **Samples** — gallery showing the 5 most recent designs
- **Pricing** — tiered options from $35 (digital file) up through prints and
  LED signs
- **FAQ** — common questions
- **Order form** — how to get started

## Tailwind config

Custom color scales defined inline:

```js
primary: sky blue scale (#0ea5e9 base)
accent:  purple scale  (#d946ef base)
```

Plus a few custom utility classes: `.gradient-text`, `.hover-lift`, `.glass`
(frosted glass effect using `backdrop-filter`).

## Sample gallery

Both pages share the same pattern — an `allSamples` array lists image
filenames from `media/`. The landing page shows the first 5; the portfolio
page shows all of them. To add new work:

1. Drop the image into `media/`
2. Add the filename to the top of `allSamples` in both `index.html`
   and `portfolio.html`
