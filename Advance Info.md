![[Music Tech advance info.png|400]]
# Large-scale analogue multitrack
## Timeline
1963 - Cassette tape invented by Philips. Quickly became standard
1966 - Recording limited to 4 tracks, releases tended to be mono still
1967 - 12 track recording (Scully), 16 track MM-1000 with 2 inch tape, first prototype 16-track studio recorder (Ampex)
1968 - 24 track recording (MCI - Sony)
1971 - At least 21 studios in London were using 16 track recording and Dolby noise reduction
1979 - TASCAM Portastudio used compact audio cassette for affordable 4 and 8 track recording (reel-to-tape tech)
70s/80s - 24 tracks became the most common format in professional recording
1980s - Digital multitrack machines began to appear in professional studios

## Other key points:
- Ability to edit, overdub -> songs did not have to be finished before entering the studio.
- Bouncing down, synchronisation of machines to create one massive project.
- 2 inch tape was used instead of 1/4 inch tape, allowing for more tracks to be played at once and more tracks to be recorded on a single tape.
- Bigger machines allowed musicians and producers the ability to experiment with more instruments and more microphones.
- les paul created sound on sound recording by modifying tape deck (device could nullify the erase function of tape recorders). Each additional pass on the tape introduced more noise, e.g. distortion 
- Companies such as SSL and Neve specialised in large mixing desks. They were fitted with distinctive sounding preamps and EQ sections and have been used on countless recordings

## ADT 1966 (Automatic/Artificial Double Tracking):
- Created by EMI technical engineer Ken Townsend for The Beatles to avoid them having to rerecord vocals to create vocal overdubs
- Used throughout the late 60s and 70s until the arrival of digital technology

## Factors that affect the sound of a tape machine/recording:
- Tape speed (signal to noise ratio)
- Wow and flutter (what are these?)
- angle of tape
- tape tension
- condition of the heads

## Original Ampex model:
- 8 tracks
- 2.1m tall, weighed 110kg
- 1.8mm tracks with 1.5mm guard track, 25mm tape
- Was known as the octopus

# DAWs
---
# Reverb
## Definition
Reverberation is the reflection of sound off a surface. Each signal is a tiny delay with some degradation of volume and quality.
![[ReverbTail.jpg|400]]

## Types of Reverb
### Natural/Room Reverb
Room reverb is the natural ambient sound of the room which is picked up in the original recording. The timbre of this sound is dependent on the surfaces in the room. Materials such as foam are often used to dampen sound, as they absorb the waves. Materials like metals are much better conductors of sound. Often studios are acoustically treated so there is little natural/room reverb.

Dry/wet balance is determined by microphone placement and positioning of the sound source(s) within the room. Initially (1920s-1950s), use of reverb was limited by speaker technology available to consumers, as the speakers could not accurately reproduce the sounds well. Therefore a lot of tracks produced in this time period are quite dry.

### Chamber Reverb
Chamber reverb was first utilised by Bill Putnam Sr in 1947. Chamber reverb consists of a concrete room with a speaker and a microphone. The dry track is played through the speaker and rerecorded with the microphone. This meant that the mixing engineer had both dry and wet signals which could be manipulated. 

![[room reverb.png|400]]
### Plate Reverb
Plate reverb was invented in 1957 by EMT (EMT 140). Plate reverb units are centered around a sheet of metal, which is suspended using a metal plate and series of springs. Similarly to spring reverb, a transducer passes the signal through the sheet metal. The signal is then rerecorded with pickup(s). A dampening plate can be used to adjust decay time. It has quite a warm sound.

![[plate reverb.png|300]]

### Spring Reverb
Spring reverb was first seen commercially in Hammond Organs in the 1930s and 40s. It was created to emulate the reverb of a church. A signal is passed through a spring with a transducer, and the signal is rerecorded with a pickup at the other end of the spring. The timbre is altered by adjusting the length of the spring and its tension. By the 1960s, the technology was licensed for used in Fender amps and Moog synths. One of its key properties is that it is fairly small (especially in comparison to a reverb chamber).

![[spring reverb circuit.png|500]]

### Digital Reverb
Algorithmic Reverb
EMT produced the first algorithmic digital reverb in 1976 (EMT 250 Electronic Reverberator Unit). A series of delays is used to mimic a natural reverb tail - reverb is essentially just delay. 

Convolution/IR/Sampling Reverb
Reverb is created by processing an impulse response (IR). An IR is a recording of a signal which contains all frequencies played in an actual room. This is to trigger the full acoustic response of the space. This is then analysed and turned into a reverb profile. Convolution reverb tends to create a more realistic sound but requires a lot more processing power.

### Gated Reverb
Gated reverb consists of a reverb which outputs to a noise gate.It was widely used in the 80s in British commercial pop. Normally, it is applied to drums to add impact to the mix whilst keeping the overall mix clean and tight. 


### Reverse Reverb
Literally just reverb that has been reversed. A good example is in Tomorrow Never Knows, by the Beatles.

## Parameters

| Term            | Definition                                                          |
| --------------- | ------------------------------------------------------------------- |
| Pre-delay       | The time between the initial signal and the early reflections.      |
| Decay time      | The amount of time it takes for the SPL to fall by 60dB.            |
| Diffusion       | The dispersion and density of reflections.                          | 
| Damping         | Absorbance of high frequencies in the reverb.                       |
| Dry/wet balance | The balance of the original signal compared to the affected signal. |

Sources:
https://www.izotope.com/en/learn/a-history-of-reverb-in-music-production.html 
https://www.izotope.com/en/learn/reflecting-on-reverb-what-it-is-and-how-to-use-it.html