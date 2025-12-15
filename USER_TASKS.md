# User Tasks & Roadmap

This project requires collaboration. As the AI, I will write the Scripts (`.cs`) and ScriptableObject definitions. **You** need to handle the Unity Editor workflow (importing assets, setting up scenes, dragging assignments).

## Phase 1: Project Setup (Do this first)
- [ ] **Install Unity**: Unity 2022.3 LTS via Unity Hub.
  - [ ] Module: **Android Build Support** (OpenJDK & SDK included).
- [ ] **New Project**:
  - [ ] Template: **3D (URP)**.
  - [ ] Name: `VR_Dating_Demo`.
  - [ ] Location: Inside `c:\Users\Admin\codezone\q2edu\` (or create the project and move my files later, but best to keep structure).
- [ ] **Switch Platform**:
  - [ ] File > Build Settings > Platform: **Android** > Switch Platform.

## Phase 2: Packages
- [ ] **Open Package Manager**:
  - [ ] Registry: Unity Registry.
  - [ ] Find & Install: **XR Interaction Toolkit**.
  - [ ] Find & Install: **XR Plugin Management**.
- [ ] **Project Settings**:
  - [ ] XR Plug-in Management > Android Tab > Check **Oculus** (or OpenXR).

## Phase 3: Assets (While I write code)
- [ ] **Character**:
  - [ ] Go to [Mixamo.com](https://www.mixamo.com/).
  - [ ] Download a character (FBX for Unity).
  - [ ] Download Animations: `Idle`, `Talking`, `Waving`, `Nodding` (No Skin / With Skin as needed).
  - [ ] Import into `Assets/Art/Characters`.
  - [ ] Set Rig > Animation Type > **Humanoid**.
- [ ] **Environment**:
  - [ ] Create a simple room using a Plane and Cubes, or import a free asset.

## Phase 4: Wiring (After I deliver code)
- [ ] Create `Dialogue` folder in `Assets/Resources`.
- [ ] Right-click > Create > Dialogue > New Node.
- [ ] Assign the `DialogueManager` script to an empty GameObject.
- [ ] Link the UI Text elements to the Manager.

---
**Please let me know once Phase 1 & 2 are complete so I can start generating the scripts.**
