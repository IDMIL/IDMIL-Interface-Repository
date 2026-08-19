## TorqueTuner

**TorqueTuner V1 (2019)**: [TORQUETUNER: ROTARY HAPTIC FORCE FEEDBACK FOR DMIS](https://www.idmil.org/project/torquetuner/)
   
 The original TorqueTuner (**TorqueTuner V1**)  is an embedded module that allows Digital Musical Instrument (DMI) designers to map sensors to parameters of haptic effects and dynamically modify rotary force feedback in real-time. TorqueTuner comes embedded with a collection of haptic effects (Wall, Magnet, Detents, Spring, Friction, Spin, Free) and a bi-directional interface through libmapper, a software library for making connections between data signals on a shared network. The platform is designed to be wireless, self-contained and built from commercially available components. The TorqueTuner has been integrated into a standalone haptic knob and into an existing DMI, the T-Stick, adding 3 musical applications (Pitch wheel, Turntable and Exciter), by mapping sensors to sound synthesis in audio programming environment SuperCollider.
 
**IDMIL Participants:**
- [Christian Frisson](https://www.idmil.org/people/christian-frisson/)
- [Marcelo M. Wanderley](https://www.idmil.org/people/marcelo-m-wanderley/)
- [Mathias Bredholt](https://www.idmil.org/people/mathias-bredholt/)
- [Mathias Kirkegaard](https://www.idmil.org/people/mathias-kirkegaard/)

**TorqueTuner V2 (2026)**: [REVIVING THE ORIGINAL TORQUETUNERt](https://www.idmil.org/project/reviving-the-original-torquetuner/)

The first iteration of the TorqueTuner, a rotary haptic force feedback module, was designed in 2019 by Mathias Kirkegaard and Christian Frisson. As discussed in Albert-Ngabo Niyonsenga’s project, Sustainable Haptic Development, the servo used to control the motor haptics, the Mechaduino, has been out of production since 2020. Since then, the TorqueTuner has been ported to the Moteus platform (2022) and more recently to the MaTouch SmartKnob (2026, SHIVERS).

This project takes a different approach to addressing sustainable haptic development by reviving the first design through a custom PCB reproducing the Mechaduino.

As a part of this project, the Mechaduino circuit design was ported from EAGLE to KiCad (a free, open-source PCB design software) and new PCB layout was routed from scratch. The design files, as well as a set of fabrication files and a protocol for flashing the ATSAMD21 MCU is provided in the project repository.

This project is still in development, though the current design (v1.2) is stable and was demonstrated at Eurohaptics 2026 alongside the other two TorqueTuners.

IDMIL Participants:
- [Danilo Pesevic](https://www.idmil.org/people/danilo-pesevic/)