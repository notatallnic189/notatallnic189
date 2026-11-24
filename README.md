# hi, I'm notatallnic189

Security tinkerer with a zero budget and one 2018 phone that refuses to die.

## Current project

**[whyred-nethunter-kernel](https://github.com/notatallnic189/whyred-nethunter-kernel)**: turns a Redmi Note 5 Pro (whyred) running LineageOS 18.1 into a Kali NetHunter platform.

- HID gadget for keystroke injection (DuckHunter style)
- external RTL8812AU adapters over OTG, signed driver in the zip
- WireGuard built into the kernel
- every build automated on GitHub Actions, no local toolchain needed

The build machinery lives in its own reusable template:
[nethunter-kernel-ci](https://github.com/notatallnic189/nethunter-kernel-ci).

Grab the [latest release](https://github.com/notatallnic189/whyred-nethunter-kernel/releases/latest) if your whyred needs a second life.
