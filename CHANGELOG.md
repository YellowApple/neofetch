## Contributors

- **[@SomaUlte](https://github.com/SomaUlte)**
- **[@jorgegonzalez](https://github.com/jorgegonzalez)**
- **[@dawidd6](https://github.com/dawidd6)**


## Operating System

- Added support for ArchBox Linux.


## Config

- Fixed default config not found.
- Don't set locale in config file.


## Info

**Shell**<br \>

- Fixed a crash when the user has `bash 3` installed.

**GPU**<br \>

- [Linux] Display detailed information about Intel GPUs. **[@SomaUlte](https://github.com/SomaUlte)**

**Color Blocks**<br \>

- Fixed issue with `color_blocks="off"` adding an extra newline to the output.

**Song**<br \>

- Fixed `mpd` detection when `mpd` is on a different host. **[@dawidd6](https://github.com/dawidd6)**


## Images

- [iTerm2] Fixed issue with linebreaks printing spaces over the image. **[@jorgegonzalez](https://github.com/jorgegonzalez)**
- Fixed issue with images not working in Terminology.
- [w3m-img] Fixed issues with `w3m-img` and `tmux`.


## Ascii

- [Windows 10] Fixed `ascii_distro` not working.
- Fixed a bug where the backend is `ascii` but the image_source is an image file.
