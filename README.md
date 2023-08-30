## Guide to Building the MagicPhoenix Kit - Differing from Voron 2.4 Manual

### Disclaimer: This guide is based on my personal experience and understanding of the build process. I am not responsible for any damage, errors, or issues that may arise during the construction. Please proceed with caution and refer to official sources for additional guidance.

**Shoutout**: A big thank you to @Livezxy, the owner of [MagicPhoenix](https://magicphoenix.xyz/), for providing this exceptional [kit](https://github.com/MagicPhoenix/MPX-VORON-24R2-CBT) and making this guide possible. Your dedication is appreciated!



**Note:** This guide provides instructions specific to the MagicPhoenix kit. For general steps, please refer to the Voron 2.4 manual.

### Page 54: Cutting the Magnetic Pad
- The magnetic pad is larger than the aluminum plate. Trim it so screw heads are exposed and edges are neat using a razor blade. For video guidance, follow [Nero's guide](https://www.youtube.com/watch?v=X2S7mkyyC4E).

### Pages 55-57: Installing Buildplate Thermistor
- The kit comes with a pre-assembled buildplate. Install the secondary buildplate thermistor (NTC100K B3950) into the screw hole to the right of the thermal fuse.
  (This is your Buildplate Thermistor.)

### Page 84: Cable Chains (Skip)
- Skip cable chain installation for X/Y axes. MagicPhoenix kit utilizes CAN-Bus.

### Page 106: X-Endstop Installation
- Install all four screws on both sides. The X-Endstop is on the toolhead; no need for later installation.
___
## ChaoticLab CNC Tap Usage:
### Page 129: Installing CNC Tap
- Leave some slack in the belt for trimming later. Follow the [ChaoticLab CNC Tap guide](https://github.com/Chaoticlab/CNC-Tap-for-Voron/blob/master/Manual/CNC_Voron_Tap_Build_Guide.pdf) up to page 5.

### Pages 139-141: Skip
- Belt clamps are integrated into ChaoticLab CNC Tap.

### Pages 143-145: Skip
- MagicPhoenix kit uses Tap, there is no need for an inductive probe.
___
### Page 146: ClockWork2 & Stealthburner Manual
- Follow the [ClockWork2 & Stealthburner manual](https://github.com/VoronDesign/Voron-Stealthburner/blob/main/Manual/Assembly_Manual_SB.pdf).
- Before installation, ensure flashing of M8P and Toolhead PCB via [this guide](https://mpx.wiki/flash-m8p-and-ebb-sb-toolboard).
- Install CAN as guided in [BTT Guide](https://github.com/bigtreetech/EBB/blob/master/EBB%20SB2240_2209%20CAN/Build%20Guide/EBB%20SB2240%202209%20CAN%20v1.0%20Build%20Guide.pdf).

### Page 148 (Electronics):
- Refer to the Voron Manual only for screw sizes. Follow the [mpx wiki](https://mpx.wiki/cbt-wiring-guide) for wiring guidance.

### Pages 150-152: Skip
- BTT CB1 on M8P replaces these components.

### Pages 158-165: Skip
- MagicPhoenix uses Tap, there is no need for a dedicated Z-Endstop.

### Pages 169-200: Skip
- Follow the [mpx wiki](https://mpx.wiki/cbt-wiring-guide) for wiring guidance.

### Page 204: Umbilical Cable Routing
- Skip until P210. For cable routing, consult the [umbilical guide](https://mpx.wiki/umbilical-guide).
  (You will have to split open the black CAN wire sleeve in order to make all the necessary connections in the electronics bay.)

### Page 231: Fan Connections
- Use the image on the [mpx wiki](https://mpx.wiki/cbt-wiring-guide) to connect fans.

### Pages 250-256: Exhaust Customization
- Skip these pages. Utilize a custom exhaust design resembling [this example](https://raw.githubusercontent.com/VoronDesign/VoronUsers/master/printer_mods/Fiction/Exhaust_cover/Images/exhaust_cover_01.png).
