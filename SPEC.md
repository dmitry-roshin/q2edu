# Project Specification: VR Dating Room Demo for Quest 2

## Goal
Create a simple VR demo scene for Meta Quest 2 using Unity XR Interaction Toolkit.  
The demo should simulate a "dating room" scenario: a small environment with a female character and basic interactive mechanics.

## Requirements

### Environment
- A single enclosed room (e.g., cozy living room or café booth).
- Minimalistic design for performance optimization on Quest 2.
- Lighting setup that highlights the character and creates an immersive atmosphere.

### Character
- Female humanoid character imported from Mixamo or Unity Asset Store.
- Idle animations (breathing, subtle gestures).
- Triggered animations (wave, smile, nod) based on player interaction.

### Interaction System
- Use Unity XR Interaction Toolkit (latest version).
- Player can:
  - Move around the room (teleport locomotion).
  - Point/select objects or character using XR Ray Interactor.
  - Trigger simple dialogue choices via VR UI (floating panel with buttons).
- Character responds with animations and text/audio feedback.

### Dialogue System
- Simple branching dialogue tree (at least 3 choices).
- Each choice triggers:
  - Character animation.
  - Text response (displayed in floating UI).
- Optional: audio playback for responses.

### Technical Constraints
- Must run on Quest 2 standalone (no PC tethering).
- Optimize for performance: baked lighting, low‑poly assets, GPU instancing.
- Use XR Interaction Toolkit prefabs where possible (Teleportation Area, XR Rig, XR UI Canvas).

### Deliverables
- Unity project with one demo scene.
- Documentation (README) explaining:
  - How to build and deploy to Quest 2.
  - How to extend dialogue and add new interactions.

## Stretch Goals (Optional)
- Basic facial animation for character.
- Ambient sound/music in the room.

