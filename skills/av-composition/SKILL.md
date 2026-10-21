---
name: av-composition
description: omnivideo stage 3 — composes the approved scenes in seek-safe HTML: the shared base of the style (motion/src/_common.html), one fork per scene all at once (beats, duration, transitions, sounds), and the closing pass (cut sheets, Passagens). Use to compose, recompose or close a video's composition after its scenes are approved. The motion script and the frames are the av-motion skill; the final render (stage 6) is the av-render skill.
model: opus
effort: xhigh
context: fork
---

!`npx -y @crievo/omni skill av-composition --v 8c0cebd02b2b --part 1/2`

!`npx -y @crievo/omni skill av-composition --v 8c0cebd02b2b --part 2/2`

Se acima aparecerem os comandos em vez das instruções, rode via Bash `npx -y @crievo/omni skill av-composition --v 8c0cebd02b2b --part i/2` para cada parte, de 1 a 2, e siga a saída.
