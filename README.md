# Dracula for [ConEmu](https://conemu.github.io/)

> A dark theme for [ConEmu](https://conemu.github.io/)

![Screenshot](https://www.dropbox.com/s/ibfrf961yukhp3b/screenshot.png?raw=1)

## Install

1. Open  `ConEmu.xml`, usually located at `%HOMEPATH%\AppData\Roaming\ConEmu.xml`.
2. Find the the key with the name `Colors`. If you don't have any custom color scheme, this key does not exists. In that case, go to **Settings** / **Feature** / **Colors** generate any custom color scheme and save it. At this point it doesn't matter what it is, as it will be overwritten.
3. Find the key with the name `Palette1`.
4. Copy the entire contents of `dracula.xml` **after** `Palette1`.
5. If you have more than one custom color scheme, rename the key of the new Dracula palette as `PaletteX`, e.g. `Palette2` if `Palette1` already exists.
6. Save `ConEmu.xml`, close and reopen ConEmu, select `Dracula` from **Settings** / **Feature** / **Colors**.
7. Optional: To set the selection color, go to **Settings** / **Keys & Macro** / **Mark/Copy** and in `color indexes` set `foreground` as `9` and `background` as `8`.

~~All instructions can be found at [draculatheme.com/conemu](https://draculatheme.com/conemu).~~

## Team

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/teeli/dracula-putty/graphs/contributors).


[![Teemu Lahti](https://avatars0.githubusercontent.com/u/294353?v=3&s=70)](https://github.com/JimmyMultani) |
--- |
[Teemu Lahti](https://github.com/teeli) |

## License

[MIT License](./LICENSE)
