# S.W.I.M (SEQUENTIAL WAVE IMPRINTING MACHINES )
The SWIM device is a novel integration of audio signal processing, LED visualization, and mechanical motion control. By capturing audio data and mapping it to light intensity on an RGB LED strip, the machine aims to translate sound into a dynamic and visually engaging format. This project builds on the principle of audio waveform visualization, bringing it into a three-dimensional space through a combination of light and motion.

**Components and System Architecture**
The project combines multiple hardware components, each playing a specific role in capturing, processing, and displaying the audio signals:
**Audio Input and Preprocessing**
Mic/Preamp Board: This component captures audio from the environment and boosts the signal to a usable level for the processing board.
3.5mm Plug to RCA Cable: Provides an alternative method for capturing audio from external sources, such as a laptop, breaking out stereo audio into left and right channels using solderable RCA jacks.

**Microcontroller and Processing Unit**
Raspberry Pi RP2040-Zero Board: The RP2040 microcontroller is the brain of the SWIM machine, responsible for processing audio signals, controlling the LED array, and managing the motor for mechanical motion. The RP2040’s dual-core architecture provides ample power for real-time processing of audio and control algorithms.

**Wave Visualization**
RGB LED Strip (144 LEDs in 1 meter): The high-density LED strip serves as the primary visual output. Each LED will correspond to a specific point in the waveform, displaying amplitude information through its color and brightness. The strip can display high-fidelity representations of sound, thanks to its high pixel density.

**Motion Control**
Stepper Motor and Driver Board: A stepper motor, controlled by a driver board, will rotate or move a surface to create a spatial dimension to the visualized waveform. This adds another layer of dynamic visual feedback, allowing viewers to see the progression of sound waves in both time and space.
