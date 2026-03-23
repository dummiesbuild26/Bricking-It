🧱 BRICKING IT
A fast-paced, mobile-first dodge game built as a single HTML file. No frameworks. No dependencies. No mercy.
Bricks fall. You dodge. Simple — until it isn't.

🎮 How to Play
Move your character left and right to dodge falling bricks. The longer you survive, the harder it gets. Pull off near-misses to rack up bonus points and build combos. Survive long enough and the game stops being polite about it.
Controls:

Mobile: Tap and hold the left/right buttons on screen
Keyboard: Arrow keys or A / D — P or Escape to pause


✨ Features

10 brick types — Normal, Fast, Heavy, Golden, Ghost, Slam, Cracked, Split, Chaos, Warning — each with unique behaviour and timing
Near-miss scoring — dodge close enough to earn bonus points and trigger combo chains
Power-ups — Shield, Slow Time, ×2 Score Multiplier, Tiny Mode, and Clear Burst
Collectible stars scattered throughout each run
Escalating stages — difficulty ramps up over time with named stage transitions and announcements
Spawn patterns — coordinated multi-brick formations that appear from Stage 1 onwards
Unlockable skins — multiple character skins unlocked through gameplay
Stats tracking — high score, longest run, total dodges, near-misses, max combo, and games played
Achievements system
Procedural audio — all sound effects generated via Web Audio API (no audio files needed)
Screen shake & particle effects — with a Low FX mode for performance-sensitive devices
Haptic feedback — vibration on mobile (toggleable)
Fully offline — one HTML file, zero external requests


🏗️ Brick Types
BrickBehaviourNormalStandard falling brickFastSmall, quick, sneakyHeavyBig, slow, takes up a lot of real estateGoldenWorth bonus points on near-missGhostPasses through you — purely psychological damageSlamHovers, then drops at speedCrackedFalls apart mid-airSplitBreaks into two bricks at a set heightChaosTiny, fast, chaotic — multiple spawn at onceWarningTelegraphs position before launching

🎨 Skins
Multiple unlockable character skins. Unlock them by playing — the game tracks your stats and rewards milestones.

⚙️ Settings

Sound on/off
Vibration on/off
Low FX mode (reduces particles for older devices)
Reset all data


🗂️ File Structure
bricking-it-final.html   ← The entire game. That's it.
This is a single-file game — HTML, CSS, JavaScript, and audio all in one place. Drop it on any static host or open it locally in a browser.

🚀 Deployment
Works on GitHub Pages, Netlify, Vercel, or literally any static host. You can also just open the file directly in a browser — no server required.

🛠️ Built With

Vanilla JavaScript (no frameworks)
HTML5 Canvas
Web Audio API (procedural sound — no audio files)
CSS custom properties + animations
localStorage for persistent stats and settings


👾 Part of Dummies Build
Built by @dummiesbuild — a project dedicated to shipping fun, weird, and shareable web apps without overcomplicating things.

"We build dumb things. Lovingly."
