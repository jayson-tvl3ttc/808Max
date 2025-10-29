# 808Max  
**A Reimagined TR-808 with Expanded Controls and MIDI Integration in Max/MSP**  


---

## Overview

**808Max** is a modern, interactive drum machine inspired by the legendary Roland TR-808, fully developed in Max/MSP. 
It combines retro aesthetics with advanced features such as real-time synthesis, MIDI integration, random pattern generation, and spatialized reverb.

---

## Motivation

The project aims to bridge the gap between **vintage hardware charm** and the **creative potential of modern software instruments**.  
While most 808 emulations focus on sound restoration, 808Max focuses on **interactivity, flexibility, and creative control**, turning the TR-808 concept into a dynamic instrument for **music creation, education, and live performance**.

---

## Core Features

-  **9 Modular Drum Synth Engines**  
  Kick, Snare, Hi-Hat, Tom, Clap, Cowbell, and more — each with independent synthesis parameters.

-  **Expanded Parameter Controls**  
  Adjustable pitch, envelope, filter, and decay settings for every sound module.

-  **Rhythm Randomizer**  
  Generates 16-step rhythmic variations with user-defined probability, balancing structure and chaos.

-  **Real-Time MIDI Integration**  
  Supports mapping to MIDI controllers (tested with Arturia MiniLab 3), enabling tactile control of sound and sequence parameters.

-  **Recording and Export**  
  Internal recording module for capturing and exporting patterns directly as audio files.

-  **Retro Aesthetic Design**  
  Interface inspired by the TR-808’s classic black-and-orange color scheme, redesigned with modular UI for clarity and workflow.

-  **Livehouse Integration**  
  808Max can serve as the sound source for the **Interactive Livehouse Acoustic Environment**, rendering drum sounds with spatial convolution using ODEON-generated IRs.

---

## System Architecture
The signal flow of 808Max moves through four core stages. It begins with global timing logic, where BPM, step length, and swing settings generate a master clock. This drives the step sequencer, which routes triggers based on the pattern grid. Each active step sends a pulse to the drum synthesis modules, where sound is generated using envelopes, filters, and noise shaping. Finally, the audio passes through spatialized convolution reverb, simulating Livehouse acoustics, before being sent to the stereo output.

<img width="1866" height="388" alt="屏幕截图 2025-10-29 004719" src="https://github.com/user-attachments/assets/dc046ca5-e238-4bf6-a75a-8ee8b44f1ea8" />

---
## User Interface Layout
<img width="1587" height="997" alt="屏幕截图 2025-05-21 193538" src="https://github.com/user-attachments/assets/9b319065-7422-4aeb-827d-7638e5a5d427" />


---

##  Future Development

-  Add **dual-lane sequencing**, **A/B pattern mode**, and **polyrhythm support**.  
-  Expand **random rhythm generator** with adjustable probability curves.  
-  Introduce **visual MIDI Learn interface** for controller mapping.  
-  Integrate **spatial audio output** with **binaural decoding** for immersive performance.  
-  Optimize patch structure for smoother performance on lower-end systems.

---

##  Technologies Used

| Category | Tool / Framework |
|-----------|------------------|
| Audio Platform | Max/MSP 8 |
| Hardware | Arturia MiniLab 3 (MIDI) |
| Synthesis Method | Procedural sound generation (oscillator + noise) |
| Interface Design | HCI principles for modular layout & feedback |
| Visualization | Custom UI color-coded in TR-808 black/orange |
| Integration | Optional spatialization with ODEON B-Format IRs |

---

##  Demo Video

Experience **808Max** in action:  
▶️ [Watch the 808Max Demo Video]([https://youtu.be/your_video_link_here](https://youtu.be/ZfJ-HfxT5DA?si=645u2l-Ezt4ePwPP))  

---

##  Author

**Jayson Chen**  
Master’s in Audio and Music Technology  
University of York  


 
---

## 📜 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute it with attribution.

---

© 2025 Jayson Chen. All rights reserved.
