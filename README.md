# workshopsynths

I have been teaching electronics workshops using simple 9V CMOS electronics for educational purposes at various artist-run spaces, festivals, and universities across Europe and North and South America since about 2007. The projects in this folder are a collection of sound circuits I have developed over the years that I wanted to archive for public use.

1. MACUMBISTA SOUNDBOX

SoundBoxes are small, primitive electro-acoustic instruments built from a wooden box, a speaker, a small LM386 audio amplifier and a contact microphone. It is designed to be built in a single day. They can create a variety of drone and reverb-type sounds through feedback between the speaker and microphone, or they can bring out the hidden sounds found within everyday objects. They also have small touchpoints which can be used to produce a variety of “circuit bending” sounds.

2. MACUMBISTA BELGIAN TRIPEL SYNTH

The Belgian Tripel is a small modular synthesizer project, which can be built over 5 days, housed in a cigar box, and run from either a 9V block battery or a 9V wall adapter (center positive). It features the following modules:

	BT-1: three voltage controlled oscillators with a square, pulse, triangle, sawtooth and reverse-sawtooth waveforms, a three channel mixer, a pulse width modulation section, and a simple power distribution system with filtering and reverse-polarity protection.

	BT-2: a non-linear, algorithmic sequencer/stepped wave generator, and a clocked digital noise generator, based on Rob Hordijk's Rungler circuit. This circuit requires two square wave inputs, one to the CLOCK input and one to the DATA input.

	BT-3: a voltage controlled, resonant low pass filter using Tim Escobedo's single-supply MS-20 clone circuit.

Stripboard layouts have been provided for all three modules. Power connectivity between the circuit boards is made by wires soldered to header pins, and front-panel, module-to-module connectivity is made with crocodile clips between M3 bolts sticking out of the cigar box.

The system is designed to be Fast and Cheap, but not necessarily Good. By that I mean that the oscillators exploit every trick I know from cheap CMOS electronics, but do not track anything like 1V/Oct and tend to jump in pitch when changing waveforms. Also note that, without additional circuitry, it cannot safely accept control voltage from a EuroRack or similar system. An impressive range of sounds can be made with it nonetheless.  

The Belgian Tripel was developed during workshops at the Univeristy of the Arts Helsinki Theater Academy (Light and Sound Department) and the RITCS | School of Arts Brussels (Radio Department) in Fall/Winter of 2017. It is inspired by the work of Rob Hordijk, Elliot Williams, Tim Escobedo, and the monks of Westmalle. 
