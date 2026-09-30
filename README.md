# WeWard — paywall rebuild, personalized from the onboarding

**Live page: https://plykhvar-glitch.github.io/weward-paywall-rebuild/**

WeWard's Premium plans screen, rebuilt in its own design and personalized with what the onboarding
already asks: the name, the answer to "What brings you to WeWard?" and the 4,500-step daily goal
the app sets. Change the answers under the phone and the paywall rewrites itself. Flip **Today**
to see the version that ships now.

## The five changes

| # | Change | Today | Now | Expected impact |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Their name and goal lead the screen | "Earn Even More Rewards & Unlock Exclusive Perks", the same for everyone | "Camille, walk more and earn 2x Wards on every step", plus a "Walk more · 4,500 steps a day" pill on the hero | CR +15–20% |
| 2 | The perks they came for, first | No perks on this screen | One line that leads with the perk matching their motivation | CR +3–8% |
| 3 | Your proof next to the price | No rating or user count on the Premium screens | 4.8 from 223K App Store ratings and 30M walkers above the plans | CR +10–15% |
| 4 | The yearly saving, said out loud | 53,88 € crossed out, no saving stated | Save 39% on the yearly card | CR +5–15% · ARPU +10–15% |
| 5 | The free week, spelled out | "Billed at 32,99 €/year" under the button | "No charge today. Free for 7 days, then 32,99 €/year" | CR +3–8% |

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
not measured lift for WeWard.*

Prices, the free week, the rating, the 30M figure and every perk come from WeWard's own App Store
listing, website and in-app screens.

## Run locally

```bash
python3 -m http.server 8000
```
