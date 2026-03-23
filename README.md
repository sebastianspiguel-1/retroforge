# RetroForge 🔁

Sprint retrospective tool built for distributed teams across the Americas.

## Features
- 4-step retro flow: Write → Group → Vote → Action Items
- Real-time sync across all participants (powered by Supabase)
- AI-powered card grouping
- Blurred cards revealed only at Step 2
- Drag & drop grouping within columns
- 👍 👎 voting with configurable votes per person
- Action items with ticket origin and vote count
- Session summary at the end

## Teams
| Team | Password |
|------|----------|
| 🛡️ Shield | `shield-retro` |
| ⚔️ Vanguard | `vanguard-retro` |
| 🏔️ Valhalla | `valhalla-retro` |

SM master password: `sm-master-2026`

## How to run a retro
1. SM creates a new retro and shares the app URL + team password
2. Everyone joins from their own device
3. Step 1 — Write cards (others are blurred)
4. Step 2 — SM advances, cards are revealed, AI groups them
5. Step 3 — Everyone votes with 👍 👎
6. Step 4 — SM creates action items per topic
7. Finish — Summary with all action items and their origin

## Stack
- Vanilla React (no build step)
- Supabase (real-time database)
- Anthropic Claude API (AI grouping)
- Hosted on Vercel
