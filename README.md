# Lokin

Lokin is a Pi-powered streak, reputation, and attention system.

## Core Principle
There is no winning.  
You either show up, or you don’t.

## How It Works
- Users check in once per day (UTC-based)
- Each check-in extends their streak
- Missing a day risks a reset (unless protected by a grace token)
- Reputation is built over time through consistency

## Features
- Daily check-in system
- Streak tracking (current + lifetime)
- Grace token system (streak protection)
- Global leaderboard (backend-driven)
- Legacy rank system
- Era system (join-based identity)
- Badge system (identity signals, not rewards)
- Founder badge (no advantage, fully playable)

## Architecture
- Frontend: Next.js (Pi App Studio export)
- Backend: Cloudflare Workers + D1
- Auth: Pi Network SDK
- Data: Backend is the single source of truth

## Philosophy
- Consistency over intensity
- Time over activity
- Identity over rewards
- Transparency builds trust

## Status
Phase B — Global system live (backend authoritative)

## Next
- Integrity layer (anti-cheat, UTC enforcement)
- Vault / reward mechanics
- Profile system and badge display
- Social competition layer