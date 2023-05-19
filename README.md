# k.audio2data
Max abstraction that converts audio from -1. &amp; 1. to integers between 1  &amp; an arbitrary value. Integers are only output when the value changes, which makes it useful to save processing power where repeated values would be unwanted (ie converting audio LFOs to MIDI CC etc)

Takes two arguments, which is the snapshot rate in ms and the data size as an int
