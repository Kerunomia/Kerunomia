<div align="center">
  <img src="https://raw.githubusercontent.com/Kerunomia/Kerunomia/main/banner.svg" width="100%" alt="keru" />
</div>

<br>

*low-level linux graphics. mostly at night.*

I write low-level Linux graphics software. Mostly Wayland compositors. The code
either runs or it doesn't, and it never asks how I'm doing. That's most of the
appeal.

I like systems small enough to hold entirely in my head. That's getting harder,
so the projects stay small and the nights get long.

---

### now

- **[vwl](https://github.com/Kerunomia/vwl)** — a tiling Wayland compositor on
  wlroots. Infinite canvas, animations, a Lua config so I don't have to
  recompile. It works, which is more than I can say for most things.
- a handful of compositor and protocol experiments that live in `/tmp` and will
  die there.

### started, not finished

- a text-mode compositor that got as far as parsing its own config
- an IPC layer for something that no longer exists
- a config format I rewrote three times and then replaced with Lua
- this readme

### what i use

```
os        openSUSE Tumbleweed
langs     C, Lua, shell
display   Wayland, wlroots, Xwayland
editor    whatever stays open
wm        mine, which is the whole problem
```

### rules i've picked up

- every program is a state machine that ends.
- someone has already written it, and they were tired too.
- if it isn't small enough to understand, I don't have it — it has me.
- the animations are staying.

---

<sub>everything compiles, eventually. or it doesn't, and that's also an answer.</sub>
