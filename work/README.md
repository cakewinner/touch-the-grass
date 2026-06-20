# Work screenshots

Drop the five screenshots here with these exact filenames. The site (`../index.html`)
references them by path and shows a labeled placeholder until each file exists, so
order doesn't matter — add them whenever.

| Filename           | Specimen | What it is                                                        | Frame ratio (≈) |
|--------------------|----------|-------------------------------------------------------------------|-----------------|
| `barter.png`       | 01       | Barter "USD-based Pool" LP builder with live position donut       | 1.37 (landscape)|
| `wrapped.png`      | 02       | Barter Wrapped 2025 tweet — "Wrapped Capybara" year-in-review     | 0.90 (portrait) |
| `skilltree.png`    | 03       | Skill Tree — radial DeFi skill graph ("X Engagement Rituals")     | 1.65 (wide)     |
| `walletmatch.png`  | 04       | Wallet Match — audience analysis / wallet-balance table           | 1.36 (landscape)|
| `lifi.png`         | 05       | Li.Fi thread — @grass_the_touch teardown of LI.FI Intents         | 0.78 (tall)     |

Each frame's `aspect-ratio` is preset in `index.html` (the `--ar` on each `.shot`)
to match the screenshot it holds, so nothing distorts or crops noticeably. If you
swap in an image with a very different shape, update that one `--ar` value.

Images are displayed with `object-fit: cover` inside a fixed-ratio polaroid frame.
For crisp results, export at roughly 2× the displayed size (frames cap at ~440px wide).
