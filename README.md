<img src="https://github.com/user-attachments/assets/a2ba3245-dfee-49b9-944a-884493774b10" width="800px">

### A simpler, modular, 90% 3D printed, 3D printer toolchanger
### Maxwell Coupling + Occam's Razor
<img src="https://github.com/user-attachments/assets/31325f4e-c43f-4515-93e2-484d81ccb187" width="400">
<img src="https://github.com/user-attachments/assets/05419af5-633a-43b1-976a-13e256da2a34" width="350">

## Table of Contents
- [About](#about)
- [Contributions](#contributions)
- [Disclaimer](#disclaimer)
- [License](#license)

## About

Typical 3D printed gadgets are laden with hyper specific parts that increases the BOM cost significantly. I tried to find a completely mechanical toolchanger and only found over-engineered designs with large BOM's and complex assembly. I designed Maxwell's Razor to use as few non-printed parts as possible, the coupling is entirely 3D printed with the most special part being a few neodymium magnets to securely attach the printheads to the gantry. In addition, the docking mechanism is completely mechanical and 3D printed as well. 

I took inspiration from the [Maxwell kinematic coupling](https://en.wikipedia.org/wiki/Kinematic_coupling) and applied [Occam's Razor](https://en.wikipedia.org/wiki/Occam%27s_razor) to the design process, the simplest solution is usually the best one. Originally, I had a press fit ball bearing on one side, with metal dowels on the other ([/metal]([./metal])). This worked great but I was dissapointed with the need to have 2 additional non printed parts, which can be hard to obtain. I was able to simplify this into a completely 3D printed coupling with [/v1](./v1).

Printing instructions are located in the respective folders for each version of the toolchanger, e.x. [/v1/README.md](./v1/README.md) or  [/metal/README.md](./metal/README.md). The current versions are only compatible with the Hypercube EVO (and maybe the original Hypercube, untested). All parts were prototyped with a refurbished Elegoo Neptune 4 I bought for 90USD and 12USD/kg PETG, so don't worry if you only have a cheap 3D printer. 

A major modification you will need is **sensorless homing**, this removes the need to redesign the X and Y endstops on the Hypercube and also makes it much easier to adapt the design to other printers. 

STEP files are also provided so that you can easily modify the parts for your use case. 

Special thanks to Scott3D for the [original Hypercube EVO design](https://www.thingiverse.com/thing:2254103).

## Contributions

If you've adapted the design for your use case, please don't hesitate to open a PR!

## Disclaimer
I am not a mechanical engineer or anything like that, just a hobbyist that's been involved in 3D printers since the RepRap days. Therefore, these modifications should be done at your own risk, etc. I am not liable for any damages that may occur as a result of the modifications in this repo.

## License

This project is distributed under the [CERN-OHL-W-2.0 license](https://github.com/evanqhuang/maxwells-razor/tree/main#CERN-OHL-W-2.0-1-ov-file). This means that modifications need to be distributed as open source. E.g. if you made a design for a Voron printer, you would have to openly distribute the modified parts only. 
