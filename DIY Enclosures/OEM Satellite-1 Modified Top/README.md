# Modified FutureProofHomes Satellite-1 enclosure top

### What's been modified

The OEM enclosure top has been modified to have the following

- Wider ports/funnels for audio input to be directed into the microphones.
- Print-in-place gaskets using `Siraya Tech TPU Air` foaming TPU

### Why was it modified

I noticed that the Satellite-1 seemed to have some "echoing" and other audio distortions happening within the input recordings and sometimes TTS and wake word activation wasn't as reliable as I thought it should be or I had to speak louder and take care to annunciate my words more-so than I would expect to have to. This all seemed to disappear when the top was removed. So I to suspect that there were several factors likely contributing to this, that weren't directly hardware related.

- The audio "in" ports/funnels on the lid/top being directed upward away from any user, unless the user was standing directly over top of the Satellite-1.
- The ports/funnels being very narrow making capturing audio more difficult when also combined with the amount of depth from the top's surface and where the the physical microphones on the PCB are located, creating a situation where the microphones were essentially trying to catch audio through a pipe pointed in a sub-optimal direction, rather than a megaphone.
- The air space under the top itself acting as an echo chamber for all ambient sounds in the immediate area and bleeding into the microphones during recording. 

The hope here was to create a situation that allows the Satellite-1's microphones to capture more audio from the surrounding area, including from sub-optimal directions and direct it into the microphones while also attempting to seal out or attenuate any ambient sound bouncing around under the Satellite-1's top. 

### Equipment used to print the modified top

- Bambu Labs H2D
- Bambu Labs AMS
- Bambu Labs AMS HT (Used with the TPU)

### Possible improvements

I might be possible to further improve this by printing a couple layers of the foaming TPU on the vertical surfaces surrounding the PCB on the top, along with the flat horizontal surface of the underside of the top above the PCB to further isolate/attenuate unwanted ambient audio. I also suspect there is a chance that the button caps on the enclosure top and how their designed are possibly amplifying this effect by vibrating when sound waves within the environment are hitting them almost acting like the bones within the inner ear. So maybe with the addition of the foaming TPU this will be absorbed/attenuated enough to no longer be a factor.

### Notes

In the pictures, you'll likely notice that the diffuser is also the same color as the rest of the enclosure top's body. This was an oversight on my part and I had forgotten to buy translucent filament. So I chose to just print it with the same filament as the rest of the top.

I also should have dried the TPU longer in order to reduce the amount of stringing and post processing required.
