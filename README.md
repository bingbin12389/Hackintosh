# Hackintosh
Install mac os to non Apple Machine
Currently support
- MSi GF63-9SC laptop: MACOS 10.14.x with Opencore 0.6.3
- PC Intel skylake 6th CPU H110 motherboard: MACOS 14.0 with Opencore 0.8.8
- Dell latitude E5400 laptop Intel coffeelake 8th CPU: MACOS 14.0 with Opencore 0.8.8

# Prepare installing
- An USB with storage > 32GB
- Disk imange mac OS x.x.x dmg
- Use Disk Genius or other Disk Utilities to partition the USB in 2 part: EFI & mac OS install partition
- Copy EFI folder to the partition EFI on USB
- Launch UEFI(BIOS) to boot from USB
- Choose install Mac OS -> do the rest of install

# Patch kext & Post install
- read the Opencore POST install guide
https://dortania.github.io/OpenCore-Post-Install/


## MSi GF63-9SC laptop:
# Features current support and running
- UHD graphic 630 : patched
- Wifi : itlwm work fine
- HDMI : patched
- Battery: have waring sign need to replace
- Audio : patched
# What not working
- NVDIA GTX 1650 : disabled

## PC Skylake:
# Features current support and running
- UHD graphic 520 : patched
- LAN: patched
- HDMI : patched
- Audio : patched
# What not working
- none

## Dell latitude E5400:
# Features current support and running
- UHD graphic 620 : patched
- LAN: patched
- HDMI : patched
- Audio : patched
- Wifi: patched with Airportitlwm
# What not working
- Sometimes booting hackintosh encounter black dim screen within 3 minutes and can adjust brightness again with Fn + F / Fn + S keys
