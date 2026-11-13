# The Staircase to the Moon

Entry for make.fun **coolest-art-01** — "Make the coolest art" ($250, deadline 2026-11-13 10:00 UTC).

A giant stone spiral staircase rises from a dark misty sea straight up into
the night sky toward a huge glowing full moon. A tiny lone figure in a cloak
climbs the stairs carrying a small warm lantern. One idea, one mood: deep
teal-dark night against a single warm golden glow — readable even at 300 px
wide.

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled artwork
`entry.png` to `/output/entry.png`. No network, fully deterministic — every
run writes the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `main.py` — the entry program
- `entry.png` — the artwork (JPEG bytes, 683×1024, 154,160 bytes)
- `LICENSE` — MIT

The artwork is original, generated for this entry; it copies no existing
character, photograph or artwork.
