# SteamVR-Controller

Hello! This repository currently contains documentation and research for a full SteamVR native controller concept that I'm designing. I plan on adding firmware source code, driver code (if necessary), assembly guides, and connections to other projects that I may be working on in the future of my VR endeavours.

Project updates, as regular as they come, may be found in the [Informal Devlog](docs/informal-devlog/_intro.md).

Also, follow my thought process for hardware on the [Hardware Considerations](docs/hardware-considerations.md) page, and feel free to discuss different options!

## Current project status (subject to change... a lot):
- [x] Ideation
- [ ] **Research**
    - [ ] Purchase of existing solutions for modding
    - [ ] Purchase of components for testing ideas
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
    - User-serviceable batteries
        - Hot swappable AA, AAA sizes (allows for standard rechargeable NiMH styles)
        - User serviceable Li-Ion battery arrays
    - Capacitive touch-pads (just an idea)
    - Custom SteamVR photoresistor sensor array attachment
    - Compatibility with VR gloves (various shapes, sizes, and designs)

## Reason for project existence:
Further documentation to be written...
