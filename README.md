# Vesktop

Vesktop is a custom Discord desktop app
but this fork removes the rainbox icon and the furry launch animation!

**Main features**:
- Vencord preinstalled
- Much more lightweight and faster than the official Discord app
- Linux Screenshare with sound & wayland
- Much better privacy, since Discord has no access to your system

**Not yet supported**:
- Global Keybinds
- see the [Roadmap](https://github.com/Vencord/Vesktop/issues/324)

![](https://github.com/Vencord/Vesktop/assets/45497981/8608a899-96a9-4027-9725-2cb02ba189fd)
![](https://github.com/Vencord/Vesktop/assets/45497981/8701e5de-52c4-4346-a990-719cb971642e)

## Installing

Just install the package of you distro :idk:

## Building from Source

Packaging will create builds in the dist/ folder

```sh
git clone https://github.com/Jan64X/Vesktop.git
cd Vesktop

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman --x64
# Or package to a directory only
pnpm package:dir
```
