# ~ M4L Devices ~

A collection of the Max for Live effects and instruments I have built.

**-------------------------------------------------------------------------------------------**

### DEVICES:
**PROCEDURAL MIDI GENERATOR:**

A Max MIDI effect for Ableton Live that generates random note values plus or minus one octave given a tonic pitch and type of musical scale. Ranges of values can be used to control the time interval between notes, the duration of the notes, and the note velocity. The FREEZE function allows for MIDI note repetition, controlled by the Freeze Rate within a range of 1ms to 1000ms.

**GRANULAR DELAY:**

The granular delay takes small snippets of the incoming signal and randomly plays them back within a range of time. The delay knob controls the max amount of time between the random grains. Length corresponds to the total time the grains will play for. The killswitch will instantly kill the output.

**GRANULAR SYNTH:**

The granular synth is monophonic Max for Live instrument. Load any audio sample, use the position knob to sweep through the file, and play back random snippets chromatically with your keyboard. Select ranges within Random Grain Length and Random Inter-Grain Length to shape the sound, along with dragging the filter.

**PITCH SHIFT DELAY:**

The pitch shift delay is simple delay with cascading or descending pitch shifting on each repeat. Pitch amount is in semitones, ranging from one octave above and below.

**WEBCAM CONTROLLER:**

Work-in-progress device. This MIDI controller takes input from a webcam, splitting the video into a 3x3 grid where each point triggers a MIDI note within a scale. Select a fundemental pitch the scale is based from, the type of scale, the rate of the notes, and the note duration to shape the output of the controller. Brightness, contrast, and saturation controls are included for better video tracking.
