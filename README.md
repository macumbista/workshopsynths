# workshopsynths

I have been teaching electronics workshops using simple 9V CMOS electronics for educational purposes at various artist-run spaces, festivals, and universities across Europe and North and South America since about 2007. The projects in this folder are a collection of sound circuits I have developed over the years that I wanted to archive for public use.

1. [TO DO] MACUMBISTA SOUNDBOX

SoundBoxes are small, primitive electro-acoustic instruments built from a wooden box, a speaker, a small LM386 audio amplifier and a contact microphone. They are designed to be built in a single day. They can create a variety of drone and reverb-type sounds through feedback between the speaker and microphone, or they can bring out the hidden sounds found within everyday objects. They also have small touchpoints which can be used to produce a variety of “circuit bending” sounds by touching with fingers or other semiconductive objects (pencil graphite traces for example), or by connecting with crocodile clips.

2. MACUMBISTA BELGIAN TRIPEL SYNTH

The Belgian Tripel is a small modular synthesizer project, which can be built over 5 days, housed in a cigar box, and run from either a 9V block battery or a 9V wall adapter (center positive). 

It features the following modules:

BT-1: three voltage controlled oscillators with a square, pulse, triangle, sawtooth and reverse-sawtooth waveforms, a three channel mixer, a pulse width modulation section, and a simple power distribution system with filtering and reverse-polarity protection.

BT-2: a non-linear, algorithmic sequencer/stepped wave generator, and a clocked digital noise generator, based on a linear feedback shift register and a simple R/2R DAC. This circuit requires two square wave inputs, one to the CLOCK input and one to the DATA input.

BT-3: a voltage controlled, resonant low pass filter using Tim Escobedo's single-supply MS-20 clone circuit. This stripboard layout originally came from a Dutch guitar pedal builders site and I cannot locate the original author. I corrected some errors and added an attentuated CV input and attentuation on the signal input. At some point I will redraw it completely to include a highpass/lowpass option as well as match the artwork for the other modules.

VCO-1-XOR / VCO-2-SYNC: these are "quick-and-dirty" Voltage Controlled Oscillators based on the 4046 Phase Locked Loop CMOS chip, designed by Martin Freeman and documented here: http://mroztronium.blogspot.com/p/quick-n-dirty-vcos.html

Stripboard layouts have been provided for all modules. Power connectivity between the circuit boards is made by wires soldered to header pins, and front-panel, module-to-module connectivity is made with crocodile clips between M3 bolts sticking out of the cigar box.

The system is designed to be Fast and Cheap, but not necessarily Good. By that I mean that, for example, the BT-1 oscillators exploit every trick I know from cheap CMOS electronics, but do not track anything like 1V/Oct and tend to jump in pitch when changing waveforms. Also note that, without additional circuitry, none of these circuits can safely accept bi-polar control voltage from a EuroRack or similar system (although Martin Freeman's documentation shows one trick with diodes reverse-biased to positive and negative/ground supply on the inputs). An impressive range of sounds can be made with them nonetheless.  

The Belgian Tripel was developed during workshops at the University of the Arts Helsinki Theater Academy (Light and Sound Department) and the RITCS | School of Arts Brussels (Radio Department) in Fall/Winter of 2017, and at Osmo/za in Ljubljana in June of 2019. It is inspired by the work of Rob Hordijk, Elliot Williams, Tim Escobedo, Martin Freeman, and the monks of Westmalle. 
