# Windows Recovery - Acer Nitro

## Problem

Windows stopped booting correctly.

The laptop entered an automatic repair loop and repeatedly showed BSOD errors.

## Errors

- 0xC0000001
- 0xC00002E3

## Troubleshooting Performed

Booted into Windows Recovery Environment.

Executed:

- sfc /scannow
- chkdsk
- DISM RestoreHealth
- bcdboot

Checked BIOS configuration.

Verified Windows Boot Manager.

Reseated RAM modules.

Disconnected CMOS battery.

Reset BIOS settings.

Created Windows 11 installation USB.

Attempted Startup Repair.

Attempted System Restore.

Attempted Reset This PC.

## Hardware Investigation

Opened the laptop.

Checked:

- RAM
- SSD
- CMOS battery
- Cooling system

## Skills Practiced

- Windows Recovery Environment
- BIOS navigation
- Boot troubleshooting
- Hardware diagnostics
- Windows repair commands

## Lessons Learned

A BSOD does not always mean damaged hardware.

Systematic troubleshooting is more effective than randomly reinstalling Windows.

## Result

The issue required multiple troubleshooting attempts across both software and hardware.

Although the laptop was not immediately recovered, the process significantly improved my understanding of:

- Windows recovery
- BIOS configuration
- Boot management
- Hardware diagnostics
- Structured troubleshooting

This was one of my first real-world Windows repair experiences.

Always verify hardware before assuming software failure.

Creating recovery media is an essential troubleshooting step.
