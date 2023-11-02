<p align="center"><a href="https://DangerKlippers.github.io/danger-klipper/"><img align="center" src="docs/img/klipper-logo.png" alt="Danger-Klipper Logo"></a></p>

[![Action Status](https://github.com/DangerKlippers/danger-klipper/actions/workflows/ci-build_test.yaml/badge.svg?branch=master)](https://github.com/DangerKlippers/danger-klipper/actions/workflows/ci-build_test.yaml)

Welcome to the Danger Klipper project!

This is a community-maintained fork of the [Klipper](https://github.com/Klipper3d/klipper) firmware.

Our goal is to support features and behavior that could be "risky" if used incorrectly.

If I want my printer to light itself on fire, I should be able to make my printer light itself on fire.

Features merged into the master branch:

- [core: No Python2 tests; No PRU boards](https://github.com/DangerKlippers/danger-klipper/pull/39)

- [fan: Normalising Fan PWM power](https://github.com/DangerKlippers/danger-klipper/pull/44) ([klipper#6307](https://github.com/Klipper3d/klipper/pull/6307))

- [fan: Reverse FAN](https://github.com/DangerKlippers/danger-klipper/pull/51) ([klipper#4983](https://github.com/Klipper3d/klipper/pull/4983))

- [heater: Modify PID without reload](https://github.com/DangerKlippers/danger-klipper/pull/35)

- [heater: Velocity PID](https://github.com/DangerKlippers/danger-klipper/pull/47) ([klipper#6272](https://github.com/Klipper3d/klipper/pull/6272))

- [gcode: Jinja2.ext.do extension](https://github.com/DangerKlippers/danger-klipper/pull/26) ([klipper#5149](https://github.com/Klipper3d/klipper/pull/5149))

- [gcode: gcode_shell_command](https://github.com/DangerKlippers/danger-klipper/pull/26) ([klipper#2173](https://github.com/Klipper3d/klipper/pull/2173) / [kiuah](https://github.com/dw-0/kiauh/blob/master/resources/gcode_shell_command.py) )

- [probe: Dockable Probe](https://github.com/DangerKlippers/danger-klipper/pull/43) ([klipper#4328](https://github.com/Klipper3d/klipper/pull/4328))

- [probe: Drop the first result](https://github.com/DangerKlippers/danger-klipper/pull/2) ([klipper#3397](https://github.com/Klipper3d/klipper/issues/3397))

- [probe: z_calibration](https://github.com/DangerKlippers/danger-klipper/pull/31) ([klipper#4614](https://github.com/Klipper3d/klipper/pull/4614) / [protoloft/z_calibration](https://github.com/protoloft/klipper_z_calibration))

- [core: danger_options](https://github.com/DangerKlippers/danger-klipper/pull/67)

- [stepper: home_current](https://github.com/DangerKlippers/danger-klipper/pull/65)

- [homing: post-home retract](https://github.com/DangerKlippers/danger-klipper/pull/65)

- [homing: sensorless minimum home distance](https://github.com/DangerKlippers/danger-klipper/pull/65)

- [virtual_sdcard: scanning of subdirectories](https://github.com/DangerKlippers/danger-klipper/pull/68) ([klipper#6327](https://github.com/Klipper3d/klipper/pull/6327))

- [retraction: z_hop while retracting](https://github.com/DangerKlippers/danger-klipper/pull/83) ([klipper#6311](https://github.com/Klipper3d/klipper/pull/6311))

- [core: git-untracked folder, plugins for user-plugins](https://github.com/DangerKlippers/danger-klipper/pull/82)

- [danger_options: allow plugins to override conflicting extras](https://github.com/DangerKlippers/danger-klipper/pull/82)

If you're feeling adventurous, take a peek at the extra features in the bleeding-edge branch:

  - [dmbutyugin's advanced-features branch](https://github.com/DangerKlippers/danger-klipper/pull/69) [dmbutyugin/advanced-features](https://github.com/dmbutyugin/klipper/commits/advanced-features)

  - [stepper: high precision stepping protocol](https://github.com/DangerKlippers/danger-klipper/pull/69)

  - [extruder: sync extruder motion with input shaper](https://github.com/DangerKlippers/danger-klipper/pull/69)

  - [extruder: new print_pa_tower utility](https://github.com/DangerKlippers/danger-klipper/pull/69)

  - [input_shaper: smooth input shapers](https://github.com/DangerKlippers/danger-klipper/pull/69)

  - [input_shaper: new print_ringing_tower utility](https://github.com/DangerKlippers/danger-klipper/pull/69)

"Dangerous Klipper for dangerous users"

Klipper is a 3d-Printer firmware. It combines the power of a general
purpose computer with one or more micro-controllers. See the
[features document](https://DangerKlippers.github.io/danger-klipper/Features.html) for more
information on why you should use Klipper.

To begin using Klipper start by
[installing](https://DangerKlippers.github.io/danger-klipper/Installation.html) it.

Klipper is Free Software. See the [license](COPYING) or read the
[documentation](https://DangerKlippers.github.io/danger-klipper/Overview.html).

[![Join me on Discord](https://discord.com/api/guilds/1029426383614648421/widget.png?style=banner2)](https://discord.gg/armchairengineeringsux)
