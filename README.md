**⚡ Chrono Shift: Entropy Bridge**

Chrono Shift: Entropy Bridge is a high-tension, fast-paced 2D suspense platformer built entirely with pure HTML5 Canvas, Vanilla JavaScript, Tailwind CSS, and the Web Audio API.
Outrun the creeping Entropy Void, navigate dynamically materializing quantum bridges, bypass tricky traps, and clear 200 procedural chambers across 10 Cyber Worlds.

**🎮 Game Overview & Core Mechanics**
Dynamic Quantum Bridges: The bridge materializes directly ahead of you as you run forward and crumbles into the void behind you.
The Entropy Void: A deadly temporal wall continuously chases you from behind—hesitating or stalling for too long means instant disintegration!
Ragebait Hazard Design: Navigate unpredictable traps, including dropping crate hurdles, pop-up surprise spikes, laser gates, and fake exits.
Checkpoint System: Activated Checkpoint Beacons save your progress. Dying respawns you immediately at your last activated checkpoint without losing chamber progress.
Web Audio Soundscape: Fully synthesized retro sound effects and dynamic heartbeat audio that accelerates as the void approaches.

**🚀 Features**
200 Solvable Chambers: Generated algorithmically using a deterministic Seeded Pseudo-Random Generator (PRNG) across 10 Cyber Worlds:
CHAPTER I: Micro Shock
CHAPTER II: Entropy Core
CHAPTER III: Trust Issues
CHAPTER IV: Decoy Protocol
CHAPTER V: Void Marathon
CHAPTER VI: Paradox Gauntlet
CHAPTER VII: Surge Rift
CHAPTER VIII: Quantum Collapse
CHAPTER IX: Event Horizon
CHAPTER X: Absolute Zero

**Tight Platformer Physics:**
2-Pass AABB Collision: Prevents floor-phasing or wall-sticking.
Coyote Time (100ms): Execute jumps even if you slip off a platform edge.
Jump Buffering (120ms): Preserves jump inputs right before landing.
Variable Jump Height: Tap for a quick low-hop or hold for maximum elevation.
Universal Cross-Platform Play: Automatically scales to fit desktop monitors, mobile phones, and tablets with touch controls.
Persistence: Save progression, unlocked chambers, death count, and checkpoints directly in browser localStorage.

**⌨️ Controls**
Desktop (Keyboard)
Key                                Action
A / Left Arrow                  Move Backward
D / Right Arrow                 Move Forward
W / Space / Up Arrow           Jump (Hold for high jump, tap for short hop)
R                              Quick Restart Chamber
P / Escape                     Pause Game
M                              Toggle Mute Sound Effects

**Mobile / Tablet (Touch Controls)**
Left / Right Thumb Buttons: Move backward and forward.
Up Button (Right Thumb): Jump.
HUD Buttons: Dedicated Pause, Mute, Quick Restart, and Chambers Menu buttons.

**🛠️ Technical Details & Stack**
Frontend: HTML5, CSS3, Tailwind CSS (via CDN)
Graphics: Native 2D Canvas API (HTML5 Canvas)
Audio Synthesizer: Pure Web Audio API (zero external .mp3 or .wav dependencies)
Icons: FontAwesome 6.4.0
Storage: Browser localStorage API

**💻 How to Run**
Clone or download this repository.
Open index.html in any modern web browser (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge).
Click START RUN or select a chamber to play! No build tools or web servers required.

**📄 License**
This project is open source and available for modification, learning, and distribution.
