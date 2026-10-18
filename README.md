# st — my build

My build of [st](https://st.suckless.org/), the suckless simple terminal for X. Upstream's own README is kept as [README.suckless](README.suckless).

## What's changed in config.h

- Fira Code at 16 px, antialiased.
- Alt as the modifier key, to match my [dwm](https://github.com/gregoryjayuk/dwm) build.

## Build

```bash
make
sudo make install
```

Needs Xlib and Xft headers. Settings live in `config.h`; `config.def.h` is upstream's default for comparison.
