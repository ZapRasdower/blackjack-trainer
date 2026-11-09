# Blackjack Strategy Trainer

A single-page trainer for blackjack basic strategy. It covers when to hit, stand, double, split or surrender, and what each mistake costs.

- **Drill**: deals random hands. You pick the play and get the right answer, the reason, and what a wrong choice costs. You can practice hard, soft, pairs, tricky hands, your weak spots, or a custom set chosen from Stats. Keys: H / S / D / P / R, then Space for the next hand.
- **Play**: full hands from a 6-deck shoe with chips and a bankroll, including splits (up to 4 hands), doubles, surrender and insurance. Every decision is graded, and each mistake shows its average cost in dollars. "Starting hands" can deal only soft hands, pairs, stiff hands, doubling hands, or your weak spots.
- **Stats**: progress over time, a leak finder that spots patterns in your mistakes, your costliest and slowest spots, breakdowns by dealer card, hand type and right play, a mastery map of the whole chart, Play session history, and CSV export.
- **Chart**: the full strategy chart with your accuracy on each spot and the average result of every option. Table rules can be switched here (H17/S17, double after split, surrender).
- **Learn**: the rules of thumb behind the chart.

The default rules are 6 decks, dealer stands on soft 17, double after split, late surrender, and blackjack pays 3:2. Mistake costs come from an exact calculation of each hand's odds that treats the shoe as fresh (an "infinite deck"). All data is stored in your browser.

It is a static page with no build step, hosted on GitHub Pages.
