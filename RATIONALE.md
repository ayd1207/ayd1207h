# Design Rationale: Neon Rhythm Reciprocity

### 1. Idea
The experience places the participant inside a real-time reactive rhythm system where every keyboard strike on keys D, F, J, or K produces synthesis-generated notes (C4, E4, G4, B4) against descending neon tiles. As the participant acts, the system reciprocates by measuring accuracy, accelerating mechanical velocity across five distinct stages, and granting aesthetic rewards or enforcing structural termination.

### 2. Premises: Feedback & Reciprocity
I combined Feedback and Reciprocity so that they operate in direct tension rather than alongside each other. Feedback provides legible, instantaneous state changes: particle bursts, timing evaluations ("PERFECT", "GREAT"), and oscillator frequency generation. However, feedback does not remain passive output. Through Reciprocity, the feedback loop dictates the system's structural behavior. Accurate execution triggers positive systemic reciprocity: scores multiply, harmonic overtones enrich the audio synthesis, and the game accelerates to higher tempo stages every five hits. Conversely, negative execution extracts structural cost: missing notes depletes one of three lives and degrades flow energy. Because of feedback, the player understands their precision; because of reciprocity, that precision transforms the machine's speed, rules, and eventual victory state.

### 3. Theoretical Grounding
The interface's feedback loops build upon Norman (2013) and his framing of signifiers and immediate feedback loops that bridge the gulf of execution and evaluation. By pairing distinct harmonic frequencies and spatial hit-lines to keyboard inputs, the system ensures zero ambiguity regarding timing errors. However, Norman’s model primarily focuses on functional usability rather than expressive tension; it does not fully address situations where escalating system feedback induces stress. 

To govern this reciprocal dialogue, I integrated Crawford (2002), who defines interactivity as a cyclic conversation of listening, thinking, and speaking between two agents. The participant’s keystrokes represent "speaking," while the engine "listens" and "speaks back" by accelerating descending speeds and altering harmonic complexity. The limitation here lies in the deterministic nature of web timers: Crawford envisions fluid conversational dialogue, whereas script-based intervals enforce rigid mechanical constraints on the human player.

### 4. What I Learned
During initial peer testing with an unbriefed participant, the default falling velocity and 15-note stage thresholds felt overly punishing, causing immediate failure before the reciprocal dialogue became perceptible. In response, I reduced the initial velocity, expanded the hit-detection window to 105 pixels, and lowered the stage transition requirement to 5 successful hits. This shift allowed testers to intuitively discover the accelerating reciprocity without external instruction.

---
### References
* Crawford, C. (2002). The Art of Interactive Design: A Euphonious and Illuminating Guide to Building Successful Software. No Starch Press.
* Norman, D. (2013). The Design of Everyday Things: Revised and Expanded Edition. Basic Books.
