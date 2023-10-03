# SteamVR-Controller
Repository for building a DIY Lighthouse VR controller

## Current project status (subject to change... a lot):
- [ ] **Ideation**
- [ ] Research
- [ ] Pre-Design
    - [ ] Proof of concept
        - Electrical components mapped out, components fit together in some way, etc.
        - Firmware design identified
        - Minimum viable product documented
    - [ ] Ideation for alternatives, spin-offs, and other designs
- [ ] Design and Manufacturing
- [ ] Replication and Testing
- [ ] Bug squashing
- [ ] Evaluation and Iteration

## Project goals:
- Create a framework for which general users with some technical knowledge can build their own SteamVR lighthouse tracked hand-held controllers from widely available and easily sourceable components
    - Controller must have feature parity or parity plus with existing mainstream VR controllers. This may include (but may not be limited to) the following functions:
        - Low latency, high accuracy 6DoF tracking
        - Button mapping
            - A
            - B
            - Joystick
            - System (SteamVR menu)
            - Grip (analogue value)
            - Trigger (analogue value)
        - Capacitive touch sensing availability
            - A, B, Joystick
- Ensure compatibility and useability with existing SteamVR-native utilities
- Design for modularity and tweakability to user-desired preferences (examples and ideas below)
    - Individual analogue grip buttons for each finger -- explicit hardware finger tracking
    - Capacitive touch sensing on trigger and grip buttons
    - Hall effect joystick replacement modules (i.e. [Gulikit Steamdeck Joystick replacement module](https://www.gulikit.com/productinfo/854122.html))
    - User-replaceable batteries
        - Hot swappable AA, AAA sizes (allows for standard rechargeable NiMH styles)
        - User serviceable Li-Ion battery arrays
    - Custom SteamVR photoresistor sensor array attachment
    - Compatibility with VR gloves (various shapes, sizes, and designs)

## Reason for project existence:
Further documentation to be written...

---

[Hardware Considerations](hardware-considerations.md)

---

Another idea is to simply take an existing HTC Vive or Vive Pro controller, disassembling it, and re-wiring all triggers to work in a different form factor.