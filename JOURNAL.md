
Made by Robin Schreiber

Repository link: https://github.com/roschreiber/Lighthouse/tree/main
Total hours so far: 1
- [x] I have a 3D printer or will be getting one before March 21st
# Lighthouse 🔦

![Lighthouse Banner](assets/banner.png)
<p align="center">[ˈlaɪthaʊs]</p>

Lighthouse is supposed to be a easy to build, open source & hackable CoreXY 3D Printer, with a huge focus on High Quality Prints.
Lighthouse is made for [Hack Club](https://hackclub.com/)'s [Infill](https://infill.hackclub.com/) YSWS, a big thanks goes out to them and Alex Ren for making this possible 🫶

## __Vorgeplänkel__
### The problem:

As of today, most 3D Printers that you buy from a company are restricted to their proprietary firmware. I for example owned two different [Elegoo](https://www.elegoo.com/) brand printers and one [Anycubic](https://www.anycubic.com/) printer, which both have the same issues:

Poor calibration from the factory, inconsistent extrusion, bent lead screws after minimal runtime, and issues with build plate leveling all have a huge impact on the overall print quality. 

Usually, especially for beginner printing enthusiasts, you expect your printer to work perfectly out of the box, with no tuning (except for regular maintenance every now and then) required. While [Bambu Lab](https://bambulab.com/) has managed to fulfill this "dream" in the last two years, their printers are heavily restricted by proprietary firmware, which is not well-received by the printing community. See [this](https://www.reddit.com/r/BambuLab/comments/1i2psvz/firmware_update_introducing_new_authorization/) for example.

I want to fix this with Lighthouse. I want to construct a printer that is easy to setup, easily hackable and actually gives you good print quality for under 200$.

### The goals:

Lighthouse **should**:

- be able to print at a reasonable printing speed without having to sacrifice print quality. I'm looking at 200mm/s - 300mm/s.
- have a build size enough to handle medium sized models, 256mm³ for example.
- should be able to print a variety of materials. PLA, TPU, PETG ...
	- It should also be able to print fiber reinforced filaments. I'm looking at Carbon Fiber PLA / PETG
	- Lighthouse will most likely not have a enclosure to stay under its 200$ cutoff. That also means that ABS & ASA are most likely **out of question** here.
- should be able to be controllable through your Wireless Network. 
  -> Fluidd UI for Klipper maybe?
  