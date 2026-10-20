# glyph

## The Keyboard

A [Corne](https://github.com/foostan/crkbd) consists of two separate boards, one under each hand. This is to allow for a more ergonomic arm and wrist posture than a traditional keyboard, with this particular version having 23 keys on each half.

## The Layout

[Gallium](https://github.com/GalileoBlues/Gallium) is an alternative to QWERTY. It places the letters so that the most commonly typed ones are easier to press, and the most common combinations of letters are optimized to minimize using the same finger twice in a row and awkward stretching of the hand. To learn more about alt keyboard layouts, see this [website](https://getreuer.info/posts/keyboards/alt-layouts/index.html).

```text
QWERTY    q w e r t    y u i o p
          a s d f g    h j k l
          z x c v b    n m

Gallium   b l d c v    j y o u
          n r t s g    p h a e i
          x q m w z    k f
```

I modified the symbol placement slightly to be more aesthetic on my keyboard. All the remaining keys that you would expect on a full sized keyboard are accessible through layers (by momentarily holding down L1 and L2).

![Keymap](images/keymap.svg)

The drawing is generated from [`keymap.yaml`](keymap.yaml) with [keymap-drawer](https://keymap-drawer.streamlit.app/).

## Sourcing Parts

A barebones version (no switches or keycaps) of the keyboard was ordered pre-assembled from Amazon. I then bought some Deap Sea silent tactile low profile Choc v2 switches and ordered custom keycaps from [fkcaps](https://custom.fkcaps.com/custom/) to complete the build.
