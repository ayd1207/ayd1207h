# Neon Rhythm Reciprocity Piano

An interactive rhythm performance exploring how sensory feedback and reciprocal systemic reaction alter player agency across escalating tempos.

## Premises Combined
* **Feedback:** Instant auditory synthesizers (Web Audio API), lane illumination, particle explosions, and textual judgment windows.
* **Reciprocity:** The system directly reciprocates the player's accuracy. Consistent hits progress the experience through 5 difficulty stages and build flow multipliers; conversely, three misses deplete player lives and trigger a complete game shutdown.

## How to Play
* **Inputs:** Use the keyboard keys **D**, **F**, **J**, and **K** (or touch/click the on-screen buttons) when the falling neon tiles reach the target hit-line.
* **Progression:** Hit 5 notes successfully per stage to advance through 5 stages of increasing speed.
* **Constraint:** You have **3 lives** (hearts). 3 misses end the performance.
* **Victory:** Complete Stage 5 to unlock the final blooming rose.

## AI Usage Statement
AI tools (Google Gemini) were utilized as an interactive programming partner for scaffolding Web Audio API oscillators, calculating hit-detection tolerances, and refactoring keybindings. 
* **Correction/Rejection Example:** The AI originally suggested a complex 15-hit threshold with continuous background music tracks and WASD keys. I rejected this design because it obscured player agency and fine-grained feedback timing, manually insisting on an accessible D-F-J-K mapping, an immediate 5-hit progressive stage engine, and strict 3-heart fail-states to heighten tension.

## Credits & Technologies
* Single-page HTML5, Tailwind CSS, Web Audio API, HTML5 Canvas.
* Built for **NMED 3203 Interactive Media Applications Lab**.
