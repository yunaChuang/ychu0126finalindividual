# Dove in the Dream – Meditation  
### Sound  
### Group D  

| Name              | Unikey     |  
|-------------------|------------|  
| Yuan-Yuan Chuang  | ychu0126   |

## Overview
This work includes a background dove and a large pop-up eye. When the mouse is pressed, it switches to dark mode, symbolising a nightmare.

In my personal work’s default mode, the visuals are calm and reflective, evoking a dreamy, bubble-like meditative atmosphere aligned with our group’s main concept. However, holding down the mouse dramatically shifts the experience into “dark mode”—the background turns black, and an electronic “alien” sound plays. In this mode, the dove becomes more unsettling, almost haunting, as if it’s watching you through the exaggerated, pop-up eye.

## How to Interact

1. **Click** anywhere on the canvas to start the music.  
2. **Hold the mouse down** on the dove to enter **Dark Mode** (I called it Cyber Mode in coding sometimes).  
3. **Move your mouse** close to the dots which shape the background of the dove to scatter them. This is the key part to interact with the dove.  
4. **Move your mouse vertically** to control the music's volume with the red ellipse.  
5. **Observe how visual elements shift** between Normal and Dark Mode — colour schemes, particle behaviour, and shapes all transform dynamically.

## My Individual Animation Approach

I focused on adding layers of **audio-driven** and **interactive animation** to enhance the shared group work. My goals were:

- Add **top-row bouncing balls** for audio amplitude visualization.  
- Introduce **mouse position volume control** for an intuitive sound experience.  
- Make a **Dark Mode** that changes both the aesthetic and audio responsiveness of the scene.

## Animation Driver

- **Main Driver:** Sound (Amplitude & FFT analysis)  
- **Secondary Driver:** Interaction (mouse position and clicks)

## Animated Properties

| Property               | Behaviour                                            | How Mine Is Different                  |
|------------------------|------------------------------------------------------|---------------------------|
| Dot motion             | Dots scatter when the mouse is nearby                | With a different dot density                    |
| Colour switching       | Dreamy colour ↔ red/green                            | I focus on the two opposite modes              | 
| Sound-reactive circles | Bouncing top-row circles tied to music amplitude     | I add a different sound in dark mode               |
| Audio-controlled glow  | Dots pulse and jitter based on amplitude             | I have the sound data to interact with              |
| Volume control         | Vertical mouse position maps to audio volume         | A key part of soound interaction                |

## Inspiration

I was inspired by:  
- [Article](https://www.auntyflo.com/dream-dictionary/dreams-about-eyes#google_vignette): Dreams and eyes are highly connected.  
- [Image](https://www.istockphoto.com/photo/close-up-image-of-racing-pigeon-eye-gm1186176382-334586206): Bird and its eye (Sorry for being scary)

## Technical Explanation

- **Dots (dove's background)** are sampled from the image’s dark pixels and scattered via vector math (direction and distance). When the mouse comes close, a repulsion force is applied. This is the main group work and I did some small changes, for example, colour and pixel density. 
- **Amplitude** controls:  
  - Side ellipses  
  - Vertical bounce of top-row circles  
  - The eye blinking  
- **FFT spectrum** is visualized through radial circular bars.  
- **Dark Mode** toggles alternate colour palettes and audio-triggered enhancements.  
- **Mouse position** is mapped to control sound volume.

## Changes to Group Code

I did some small changes of the group code to make my personal work has a higher consistency
- The colour of the background dots  
- The density of the background dots  
- A slight change in the way the dots scatter  

## Tools & External Techniques

- ChatGPT helped a lot in explaining the code and improving my understanding of p5.js. I had all the ideas myself and tried to develop them based on what we learned in the course. But sometimes it was hard to achieve exactly what I imagined, so I used AI tool to help better express and implement my thoughts. Most of the time, I asked ChatGPT to tell me the code and explain them step by step. After getting the code, I always adjusted the parameters in the code made it more fits in the design.
[ChatGPT](https://chatgpt.com/share/6847ee6c-e658-800f-8483-6ed4ac311111)
[ChatGPT](https://chatgpt.com/share/6847eee5-7f98-800f-b918-23e87253133e)
[ChatGPT](https://chatgpt.com/share/6847ef20-93a0-800f-baa3-6d54d8a697e4)
- [p5.js](https://p5js.org) p5.js helped me a lot in understanding how the code works and allowed me to realise how to use it in a simple and basic way.

## Reference
Close. (2019, November 14). *Close up image of racing pigeon eye. IStock.* https://www.istockphoto.com/photo/close-up-image-of-racing-pigeon-eye-gm1186176382-334586206

*Dreams About Eyes.* (2018). Auntyflo.com. https://www.auntyflo.com/dream-dictionary/dreams-about-eyes#google_vignette

(Sample Pack Link In Bio - Alien I Trust) Who defines life - If thought is life - then I am eternal by Alien_I_Trust. (2025). *Freesound.* https://freesound.org/people/Alien_I_Trust/sounds/785804/

Piano loops 093 efect 4 octave long loop 120 bpm by josefpres. (2025). *Freesound.* https://freesound.org/people/josefpres/sounds/810839/