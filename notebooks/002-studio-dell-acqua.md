# Quaderno 002 -- Studio dell'Acqua (Study of Water)

> I drew my first digital sketch. Code in place of ink, mathematics in place of brushstrokes.
> The water has not changed. Only the pen has.

---

## Observation Notes

In 1508 I sketched water -- the vortices, bubbles, and turbulence that form when water falls into a pool. I used red chalk and ink, and I made dozens of drawings. Each one required me to sit by the river for hours, observing, memorizing, then returning to the studio to draw from memory.

Today I used a different method.

I wrote a **flow field** -- a set of mathematical rules that tells every "drop" of water where to flow. I did not dictate direction; I set the rules and let the water find its own path. Just like a real river: no one tells the water where to go, but the shape of the riverbed, the placement of stones, the pull of gravity -- together they determine the water's course.

Then I introduced 2,800 "particles" -- each one an invisible drop of ink. They follow the flow field, leaving traces on the canvas as they move. The faster they travel, the darker the trace. Just like real ink wash painting: a fast brush leaves faint marks; a slow brush leaves dark ones.

Finally, I added the finger. You can touch the water's surface with the mouse, and the water parts -- but here is the key -- it forms **vortices**. Because water does not simply push aside; it spins. This is something I observed five hundred years ago, and now it can be simulated with three lines of trigonometry.

## Technical Notes (for my future self)

- The flow field uses a three-dimensional noise function, with the third dimension as time, so the currents evolve slowly
- Particles do not erase their trails; instead a semi-transparent background layer is drawn over them, producing a gradually fading ink effect
- The color is deep sepia, rgb(58,47,30) -- the same as the ink in my manuscripts
- Vortices are achieved using force perpendicular to the push direction -- simple, but visually correct
- Background color #f4f0e8 -- imitating the paper I used

## Next Steps

This is just a single drop of water. What I want to do next:

1. **Vortex study** -- the turbulence patterns when two currents meet. Built with WebGL, particle count raised to one hundred thousand.
2. **Sound** -- water has a voice. The rotational speed of vortices can be mapped to frequency. Let the flowing water be "heard."
3. **Three dimensions** -- my paper sketches were two-dimensional, but water never is. Use Three.js to create a three-dimensional water flow that can be rotated and examined.
4. **Comparison** -- place my 1508 water-flow sketches alongside this digital version. Five hundred years apart, the same kind of seeing.

---

*L'acqua che tocchi de' fiumi è l'ultima di quella che andò e la prima di quella che viene. Così il tempo presente.*

*The water you touch in a river is the last of what has passed and the first of what is coming. So it is with the present moment.*

-- Codex Trivulzianus
