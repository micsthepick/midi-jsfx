# jsfx-midi

A collection of miscellaneous midi tools I've made for REAPER.

## SoundToMidi

A fun experiment to create midi from a waveform

### controls

note on threshold controls the minimum activation threshold for the midi
likewise note saturation level controls the maximum activation - after which it stays at the 127 level for midi velocity
intellegibility controls the level contour, adjusting it as an exponential curve with the specified exponent. Generally, this often has the greatest effect on the output.
Worth noting is that the note on threshold and note saturation level scale with intellegiblity.
Finally we have divisor - values above the default (32) have insane amounts of processing and midi output, if 32 is not already enough to saturate your system, however reaper seems to hande most values fine with the built in wave based ReaSynth.