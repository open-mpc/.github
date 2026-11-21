# Open MPC

**A community project for everything that makes Akai MPC hardware do more.**

Open MPC brings together the information, work and development that extend the MPC experience: plugins, controller
support, OS tweaks and addins, tools, and the research behind them. It covers the MPC Gen1 and Gen2 Standalone devices as well as the MPC Sample series.

MPCs are made for music, and so is most of what's here. But an MPC is also a Linux computer with pads, knobs and a
touchscreen, which makes it something you can build on. Whether you want to make beats, design a synth, reverse-engineer
a protocol or draw a skin, there's room for all kinds of creativity here.

[**Discord**](https://discord.gg/sRRysZSgu3) · [**Plugin catalog**](https://open-mpc.github.io/) · [Install the Plugin Manager](https://open-mpc.github.io/install.html) · [Build guide](https://open-mpc.github.io/build.html)

## What the community works on

**Plugins.** Synths, samplers, drum machines, effects and sequencers that run natively in MPC's own plugin host, each
with its own touchscreen page and Q-Links. More than 300 are listed in the [catalog](https://open-mpc.github.io/), with
the hardware they've been tested on, and the on-device [Plugin Manager](https://github.com/open-mpc/plugin-manager)
installs them without a computer.

**Controllers.** MPC 3.10's Lua controller scripts are barely documented, so the community tests them on real hardware
and writes up what works: clip grids, mixers, named Q-Links. There are scripts for Launchpad, Launch Control XL,
nanoKONTROL, and a Force used as a second surface for an MPC.

**The OS and tweaks.** Addins that MPC loads at startup (web remote control, USB audio, a rolling recorder), opt-in
device patches (16-pad drum layout, button remaps, auto exec), and notes on how the firmware works.

**Tools.** A porting toolchain, a skin designer, host tests, CPU benchmarks, installers, and a way to run MPC plugins
in a desktop DAW.

**Knowledge.** Findings, how-tos and dead ends, written down so the next person doesn't have to redo the digging.

## Repositories

| | |
|---|---|
| [**mpc-vst-plugins**](https://github.com/open-mpc/mpc-vst-plugins) | Plugin toolchain, porting guide, addins, device patches, installer app and the catalog registry. |
| [**plugin-manager**](https://github.com/open-mpc/plugin-manager) | Browse, install and update plugins on the MPC itself, from its screen or a phone browser. |
| [**mpc-controllers**](https://github.com/open-mpc/mpc-controllers) | What MPC Lua controller scripts can and cannot do, verified on hardware, plus community scripts. |
| [**skin-studio-2**](https://github.com/open-mpc/skin-studio-2) | Desktop app to design, preview and install plugin touchscreen skins. |
| [**mpc-vst-desktop**](https://github.com/open-mpc/mpc-vst-desktop) | MPC plugins on a desktop DAW, rebuilt as VST3 or hosted under an ARM emulator. |
| [**open-mpc.github.io**](https://github.com/open-mpc/open-mpc.github.io) | The website and plugin catalog. |

Plugins built with Akai's [MPC Plugin SDK](https://github.com/inmusic-software/mpc-plugin-builder-sdk) are welcome in
the catalog alongside the community's own.

## Get involved

You don't need to be a programmer, and you don't need permission. Bring what you're good at.

- **Musicians:** try plugins and scripts on your device and say how they run. Hardware reports are what the catalog's
  test status is built on.
- **Plugin developers:** port an open-source engine
  ([porting guide](https://github.com/open-mpc/mpc-vst-plugins/blob/main/docs/PORTING.md)) or list a plugin you've built.
- **Controller tinkerers:** get a controller driving your MPC and add it to the
  [community scripts](https://github.com/open-mpc/mpc-controllers#community-scripts).
- **OS hackers:** write an addin, a device patch, or a finding about how MPC OS works.
- **Designers:** make plugin pages with [Skin Studio 2](https://github.com/open-mpc/skin-studio-2) that look like the
  hardware they came from.
- **Writers and helpers:** improve the docs, file bugs, answer questions.

Have an idea that doesn't fit any of these? That's welcome too. Say hello on [Discord](https://discord.gg/sRRysZSgu3):
it's where releases are announced, ideas get kicked around and people help each other out.

## Credits

Open MPC builds on the work of everyone who wrote the original engines, tools and research. Each project credits its
upstream authors and licences in its own repo. Thank you to everyone who builds, tests, reports and shares.

<sub>Open MPC is an independent community project and is not affiliated with or endorsed by Akai Professional or inMusic.
MPC and Force are trademarks of their respective owners.</sub>
