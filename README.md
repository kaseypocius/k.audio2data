# k.audio2midi
Max abstraction that converts audio from -1. &amp; 1. to integers between 1  &amp; 127. Integers are only output when the value changes, which makes it useful to save processing power where repeated values would be unwanted (ie converting audio LFOs to MIDI CC etc)

Takes one argument, which is the snapshot rate in ms
