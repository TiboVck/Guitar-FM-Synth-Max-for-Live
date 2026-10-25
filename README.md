# Guitar FM Synth - Max for Live

An experimental Max for Live plugin turning an electric guitar into an FM synthesis controller.

## Concept

Frequency Modulation (FM) synthesis works by modulating the frequency of a carrier oscillator with another signal, called the modulator. The modulator changes the carrier's instantaneous frequency, producing new harmonics and timbral variations.

In this project, the guitar itself becomes the modulator:

The plugin receives the electric guitar signal.

It detects the fundamental frequency of the played note.

A carrier oscillator is tuned to the detected frequency.

The guitar signal modulates the carrier's frequency in real time.

The resulting signal combines the pitch information of the guitar with the complex harmonic content of FM synthesis.

This creates a playable hybrid instrument where the guitar controls both the pitch and the timbre of the synthesized sound.

## Built with

- Max/MSP

- Max for Live

- Electric guitar

- Real-time pitch detection

- Frequency Modulation synthesis

## Conceptual signal flow

Electric Guitar → Pitch Detection → Carrier Frequency

Electric Guitar ─────────────────→ FM Modulator

Carrier Oscillator + FM → Synthesized Output
