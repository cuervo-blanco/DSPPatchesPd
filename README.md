# DSP Examples

### Directory

## Modulation
A module showing the creation and usage of a variable shape LFO.

- **[modulator.pd](modulation/modulator.pd)**
  A simple modulator and examples.

- **[modulationExample.pd](modulation/modulationExample.pd)**
  A patch that shows simple Amplitude Modulation of waves. With Sound Test.

- **[modulationExample2.pd](modulation/modulationExample2.pd)**
  A patch showing the usage of modulator with variable LFO shape. With Sound Test.


## Correlation
A module showcasing correlation and related algorithms

- **[correlation.pd](correlation/correlation.pd)**
    A simple Pearson correlation coefficient calculator between two input signals.

- **[correlationExample1.pd](correlation/correlationExample1.pd)**
    An example with the usage of the correlation object.

- **[correlationGUI.pd](correlation/correlationGUI.pd)**
    A wrapper of the correlation object with a meter from -1 to 1.

- **[offlineCorrelation.pd](correlation/offlineCorrelaton.pd)**
    An offline correlator to analyze correlation between two audio files.

## Saturation
A module with saturation effects and examples

- **[hard-clipper~.pd](saturation/hard-clipper~.pd)**
    A basic hard clipper that uses clip~ under the hood and compensates
    amplitude.
- **[hardClipperExample1.pd](saturation/hardClipperExample1.pd)**
    A patch that takes in input signal, and based on a dB slider calculates
    amount of clipping.
