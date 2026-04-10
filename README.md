# NEURO-REACTOR

**Live Demo:** 
- [https://dmitry-sukhoruchkin.github.io/NEURO-REACTOR/](https://dmitry-sukhoruchkin.github.io/NEURO-REACTOR/)
- [https://neuroidss.github.io/NEURO-REACTOR/](https://neuroidss.github.io/NEURO-REACTOR/)

Neuro-Reactor is a real-time Brain-Computer Interface (BCI) simulation and game designed to test and decode spatial attention, motor intent, and cognitive states using raw EEG data (8 channels).

Unlike traditional P300 spellers that rely on reactive evoked potentials, Neuro-Reactor decodes **proactive, continuous brain states** using advanced signal processing and real-time audio-visual biofeedback.

## Core Mechanics & Science

### 1. Movement (Motor Intent via Coherence)
Avatar movement is controlled by analyzing the **symmetry breaking and coherence** in the Beta and Lower Gamma bands across the hemispheres. 
- The brain learns to navigate (forward, backward, turn) by modulating these symmetries. 
- This acts as a "virtual gamepad" that the brain adapts to through neuroplasticity and operant conditioning.

### 2. Telekinesis & Interaction (Spatial Attention via Theta-Gamma PAC)
Interaction with objects (pulling energy orbs, unlocking chests) is driven by **Theta-Gamma Phase-Amplitude Coupling (PAC)**. This is the brain's "native language" for spatial navigation and memory, requiring less training than motor imagery.

We decode the temporal structure of the EEG signal relative to the Theta peak (The "Present"):
- **The Present (Theta, ~6Hz):** Acts as the internal clock and phase reference.
- **The Past (Slow Gamma, 31-51Hz):** Appears on the descending phase of Theta. Represents memory retrieval and context.
- **The Future (Fast Gamma, 61-102Hz):** Appears on the ascending phase of Theta. Represents sensory prediction and spatial intent.

### 3. Structural Analytics: The Population Vector & Sharpness
Instead of reducing the complex 8-channel EEG data to a single "focus" number, the system analyzes the **spatial distribution** of the Fast Gamma (Future) across the cortex:
- **Population Vector (Direction):** By mapping the 8 electrodes to physical angles, we calculate a 2D vector representing the exact direction of spatial attention (the "Radar Beam").
- **Sharpness (Focus Quality):** We measure the variance/entropy of the Fast Gamma across the 8 channels. 
  - *Diffuse Attention:* All channels show equal Fast Gamma. The radar is a wide, weak circle.
  - *Sharp Attention:* 1 or 2 channels spike significantly higher than the rest. The radar becomes a sharp, highly directional beam capable of locking onto specific objects.

## Audio Biofeedback (The Brain's Mirror)
To help the brain recognize its own states, the app features real-time sonification:
- A base frequency pulses at the Theta rate (6Hz).
- The volume and harmonic richness increase as the Theta-Gamma PAC strengthens.
- When the Population Vector successfully locks onto an interactable object, the frequency shifts to a resonant 432Hz, providing instant reward and confirmation to the neural networks.

## How to Test
1. Click **CONNECT BLE** to pair your 8-channel EEG headset.
2. Use motor intent to navigate the maze.
3. To interact with Orbs or Chests, direct your spatial attention towards them. You will see your "Attention Radar" (purple polygon) stretch in the direction of your focus.
4. Achieve high "Sharpness" to lock on and trigger the telekinesis/unlock mechanics.
