# ferris-layout

## How to Edit

Look at the general how to use qmk + ferris markdown file called ben_qmk_ferris.md, this should give the gist of what to do.

But also check out these two videos for more context:

- [How to flash firmware on your keyboard using QMK - Ferris Sweep](https://www.youtube.com/watch?v=HjLx8C5f4mM)
- [The Best 34 Key Keymap For People Coming From Normal Keyboards - Ferris Sweep Keymap](https://www.youtube.com/watch?v=VShLPvF693k&t=632s)

## Commands to run to build qmk:

1. cp /Users/samroberts/Code/ferris_layout/\* /Users/samroberts/qmk_firmware/keyboards/ferris/keymaps/ben
2. qmk compile -kb ferris/sweep -km ben
3. cp -r /Users/samroberts/qmk_firmware/.build/\* /Users/samroberts/Documents/ferris_layout

then, open QMK and flash
