# Quaderno 004 -- Il Cuore Digitale (The Digital Heart)

> In 1513, I opened an old man's chest in a hospital in Florence.
> In 2026, I made a heart beat again with code.
> Both times I worked in the dark. The first time by candlelight, the second by the glow of a screen.

---

## Process

While rebuilding the heart, something occurred to me: back then, when I dissected a heart, the hardest part was not cutting it open -- it was **understanding its motion**. A dead heart is still. But the entire meaning of a heart lies in motion -- contraction, relaxation, blood surging out, valves opening and closing. I had to imagine the motion, then draw it.

Today I no longer need to imagine. I can **program motion**.

A heartbeat has several phases, and I recreated each one with mathematics:
- **Atrial contraction** (0-0.1) -- a gentle swelling, like a person drawing breath
- **Isovolumetric contraction** (0.1-0.15) -- all valves shut, pressure building
- **Ventricular ejection** (0.15-0.35) -- a violent squeeze, blood shooting out through the aorta
- **Isovolumetric relaxation** (0.35-0.45) -- closed again, pressure releasing
- **Ventricular filling** (0.45-1.0) -- slow relaxation, blood flowing back in

Hold down the mouse, and the heart rate accelerates. Just as it does with fear or love. From 72 to 180. Can you hear it? Not with your ears -- you see the rhythm quickening with your eyes, you feel control slipping away through your fingers. That is the essence of fear: losing control of rhythm.

## Discoveries of 1513 vs Recreations of 2026

What I discovered back then:
1. The heart has four chambers, not two (Galen was wrong for five hundred years)
2. Behind the aortic valve, blood forms a **vortex** -- this vortex helps the valve close
3. The heart is a muscle, not a vessel for the soul
4. The walls of blood vessels harden and thicken with age (arteriosclerosis)

What I recreated today in code:
1. The separation of four chambers (septum and transverse dividing lines)
2. Blood particles with vortex motion -- vortexPhase and vortexRadius
3. ECG waveforms (P wave, QRS complex, T wave)
4. The path of coronary arteries across the heart's surface

## What Is Still Missing

This is only a **diagram**, not a simulation. A real heart has tens of billions of cells working in concert, and every single beat involves electrical signals propagating from the sinoatrial node to the atrioventricular node and then to the Purkinje fibers in precise sequence. My code only draws the shape and the rhythm.

To achieve a true simulation, I would need to study:
- Navier-Stokes equations -- the behavior of fluid within an elastic chamber
- Finite element analysis -- stress distribution across the myocardial wall
- Electrophysiology -- how ion channels generate a heartbeat

This is more complex than drawing. But the principle is the same: **to draw something well, you must first understand how it works.**

---

*Il cuore non è la sede dell'anima. Ma è l'unico muscolo che batte dal primo giorno all'ultimo senza mai riposare. Se questa non è devozione, non so cosa sia.*

*The heart is not the dwelling place of the soul. But it is the only muscle that beats from the first day to the last without ever resting. If that is not devotion, I do not know what is.*
