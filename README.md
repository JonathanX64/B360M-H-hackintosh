# My Hackintosh build
Specs + changelog + EFI folder (if you need an example or want to use it with similar hardware)

## Hardware
- Gigabyte B360M H
- Intel Core i5-8400
- 2x16 GB DDR4-2666 XMP (Corsair Vengeance)
- Samsung 960 Evo 500 GB NVMe storage
- AMD Radeon RX 460 4 GB (Gigabyte)
- Broadcom BCM94360CD (Fenvi T919) 

## Software
OpenCore 0.6.3
macOS Big Sur 11.1

## Installation
Went smooth af, followed the usual [guide](https://dortania.github.io/OpenCore-Install-Guide/)

## Performance
Subjective: as fast as it could ever get
Geekbench 5: [1004/5118](https://dortania.github.io/OpenCore-Install-Guide/)
Geekbench 5 Compute: [19705](https://dortania.github.io/OpenCore-Install-Guide/)
Blackmagic Disk Speed Test: 1800 write/2500 read
Cinebench R23: 1017 single-core/5674 multi-core

## What works 
Everything except...

## What doesn't / to-do list
- [ ] Fix audio layout
- [ ] Write a USB map
- [ ] Upgrade OpenCore to 0.6.4
- [ ] Fix key mapping for my keyboard
- [ ] Fix DRM with `shikigva=80`
- [ ] Apply other post-install tweaks

## Backstory of this build
I had an iMac 5K (Late 2015) in top-of-the-line-but-not-custom configuration: i5-6600, 16 GB DDR3-1866, Radeon R9 M395 2 GB, 2TB Fusion Drive (128 GB flash & 2 TB HDD).

It ran slower than I expected and had some annoying problems. To fix the machine, I had to disassemble it, replace noisy cooling system, replace hard drive, replace flash storage, and add more memory. Or just sell it and get a newer one (Apple's way of fixing things™).

Above-mentioned upgrades are expensive. New Apple 256 GB Gen. 5B SSD have insane prices, and 4x8 or 2x16 sticks of DDR3-1866 are impossible to source these days. Plus, I had to pay for disassembly and reassembly of this computer (or risk breaking the display). 

So I've sold it... but built a Hackintosh instead! I was aiming at 2x performance for 0.5x of second-hand market price of this iMac, and I think I got it. Excited! 

## Acknowledgments
* Apple for macOS
* Apple for making insanely expensive but cool Intel machines that plead to be hackintoshed
* Dorthania for the guides
* Hackintosh community for everything