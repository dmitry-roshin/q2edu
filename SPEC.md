# Project Specification: VR Dating Room Demo for Quest 2

## Goal
Create a standalone VR demo scene for Meta Quest 2 using **Unity 2022.3 LTS (URP)** and **XR Interaction Toolkit 3.x**.
The demo simulates a "dating room" scenario interaction with a humanoid character.

## Technical Requirements

### Engine & Pipeline
- **Unity Version**: 2022.3 LTS (Long Term Support).
- **Render Pipeline**: Universal Render Pipeline (URP) - Optimized for Mobile VR.
- **Color Space**: Linear.
- **Target Platform**: Android (Meta Quest 2).

### Interaction System
- **Framework**: XR Interaction Toolkit (XRI) 3.x.
- **Locomotion**: Teleportation Area / Anchor.
- **Input**: Action-based Input System (OpenXR / Oculus).
- **Interactors**: XR Ray Interactor (for UI and Teleport).

### System Architecture

#### 1. Dialogue System (ScriptableObjects)
To ensure easy extensibility, dialogues will be data-driven.
- **Data Structure**: Nodes configured as `ScriptableObject` assets.
- **Features**:
  - Speaker Name.
  - Dialogue Text.
  - Linked Animation Trigger (e.g., "Wave", "Shy").
  - Array of Choices (Text + Link to next Node).

#### 2. Character Controller
- **Animator Integration**: System will drive the `Animator` component parameters.
- **States**:
  - `Idle` (Loop).
  - `Talking` (Bool/Trigger).
  - One-shot actions (`Wave`, `Nod`, `Laugh`).

#### 3. User Interface
- **World Space Canvas**: Floating UI panel near the character.
- **Dynamic Buttons**: Instantiated at runtime based on available choices.

### Graphical Assets
- **Environment**: Low-poly room (baked lighting recommended).
- **Character**: Humanoid Rig (Mixamo-compatible).

## Deliverables
- Unity Project folder.
- `Assets/Scripts/` containing the C# logic.
- `USER_TASKS.md` guide for setup.
