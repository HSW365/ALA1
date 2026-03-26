# ALA1 - Cyberpunk Claw Machine

⚡ **Charge your drop. Time the grab. Steal the prize.** ⚡

A cyberpunk-themed physics claw machine built with Next.js 14, Matter.js, and Tone.js.

![Cyberpunk Claw Machine](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![Matter.js](https://img.shields.io/badge/Matter.js-Physics-orange?style=for-the-badge)
![Tone.js](https://img.shields.io/badge/Tone.js-Audio-yellow?style=for-the-badge)

## Features

- 🎮 **Real-time Physics** - Powered by Matter.js
- 🎵 **Procedural Audio** - Synthesized with Tone.js
- 🌈 **Neon Cyberpunk Aesthetic** - CSS animations and gradients
- 📳 **Haptic Feedback** - Mobile vibration support
- 🔗 **Combo System** - Chain successful grabs for multipliers
- 🏆 **Golden Hexagons** - Rare prizes worth 10x points
- 🔐 **Secure Auth** - Supabase authentication integration

## Game Mechanics

1. **CHARGE** - Hold the button to power up (oscillating movement)
2. **TIME** - Release at max power for optimal position
3. **GRAB** - The claw drops and attempts to grab a prize
4. **COLLECT** - Guide the prize to the chute for points
5. **COMBO** - Chain successful grabs for score multipliers

## Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Physics**: Matter.js
- **Audio**: Tone.js
- **Auth**: Supabase Auth
- **Deployment**: Vercel
- **Language**: TypeScript

## Local Development

```bash
# Clone the repository
git clone https://github.com/HSW365/ALA1.git
cd ALA1

# Install dependencies
npm install

# Set up environment variables
cp .env.local.example .env.local
# Edit .env.local with your Supabase credentials

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to play.

## Environment Variables

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_supabase_service_role_key
```

## Deployment

### Vercel (Recommended)

1. Push to GitHub
2. Import project in Vercel
3. Add environment variables
4. Deploy!

```bash
# Using Vercel CLI
vercel
```

### Manual Build

```bash
npm run build
npm start
```

## Controls

| Input | Action |
|-------|--------|
| Mouse/Touch | Move claw horizontally |
| Hold CHARGE | Power up with oscillation |
| Release/DROP | Drop the claw |
| Spacebar | Keyboard alternative |

## Scoring

- Standard Prize: 10 points
- Golden Hexagon: 100 points
- Combo Multiplier: +50% per consecutive grab

## License

MIT License - See [LICENSE](LICENSE) for details.

---

**ALA1** - *First contact. Steal the prize.*
