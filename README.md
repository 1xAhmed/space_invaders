# Space Invaders

Invaders is an open source terminal arcade game with audio, based off of the "Space Invaders" classic arcade game.

This game was initially developed for a presentation at [OSCON Open Source Software Superstream Series: Live Coding—Go, Rust, and Python](https://learning.oreilly.com/live-training/courses/oscon-open-source-software-superstream-series-live-codinggo-rust-and-python/0636920410188/) and then adapted for inclusion as an example project for the  [Rust Crash Course](https://github.com/1xAhmed/rust_crash_course/). 

Since the original presentations, folks continue to tinker and improve the game. Feel free to fork this repository, make a change, and submit a pull request if you have a good idea!


### Dependencies on Linux

Audio should work out-of-the-box on macOS, Windows, and iOS.  For Linux, the
downstream package for actually _playing_ sound ([CPAL]) requires
the *Alsa* development libraries to be installed.

**CentOS**

```bash
sudo yum install -y alsa-lib-devel
```

**Debian/Ubuntu**

```bash
sudo apt install libasound2-dev pkg-config
```
**Arch Linux**

```bash
sudo pacman -S alsa-lib pkgconf libx11
```
You will also need `pipewire-alsa` or `pulseaudio-alsa` depending on the sound server you are using.

## Community Games!

Were you inspired to make your own terminal-based game? Open a PR to add it to the list here!

* [Pong](https://github.com/basilkohler/rusty_pong)
* [TETRIS](https://github.com/madchicken/rust-tetris)
* [Columns](https://github.com/Rendez/rust_columns)
