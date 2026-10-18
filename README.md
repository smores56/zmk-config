ZMK Config
==========

My [ZMK][zmk] config for the [Osprette][osprette] and [Clog][clog] keyboards.

`build.yaml` lists every board and shield combination that gets built. All the
boards share one layout, `config/34-key.keymap`; the per-board keymaps just
include it. Firmware is built by the [ZMK build action][action] on every push
and published as workflow artifacts.

The `clog` and `osprette` shields come from upstream ZMK. `clog_v2` (XIAO BLE)
and `geta` (the Clog V4 codename) are defined here. `the_paintbrush` is a
borrowed shield for a board I didn't design.

[zmk]: https://zmk.dev/
[osprette]: https://github.com/smores56/osprette
[clog]: https://github.com/smores56/clog
[action]: https://github.com/zmkfirmware/zmk/.github/workflows/build-user-config.yml
