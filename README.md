# Tierwriter

<img src="https://github.com/jyuenger/Tierwriter/blob/9abbb466a296ae63d2cabd3b20eebf0fafaae6d2/documentation/Mockup.png" width="300">


A tiered, typewriter-style, handwired 60% mechanical keyboard with arrows, 7u/8u spacebar, and UK ISO support

## Things You'll Need:
- A controller ([Stampy RP2040](https://keeb.io/products/stampy-rp2040-usb-c-controller-board-for-handwiring)) and firmware (UF2 files in the Firmware folder)
- Five custom 1.5mm thick switchplates, one for each row (AI files for lasercutting in the Plate folder; Alps/MX version is in the Alps subfolder)
- Two stepped support wedges (STL file for 3D printing in the STL folder)
- Ten M3 8mm screws (four more if you want to screw the undersides of the wedges to a base plate)
- Ten M3 threaded inserts to heat-set into the holes in the support wedges (four more if you want to install threaded inserts into the holes on the undersides of the wedges, intended for mounting the whole assembly into a base plate or future case)
- An MX or Alps keycap set with the following nonstandard keys - 1.5u R2 backspace, 1.5u R3 Enter, 7U or 8U spacebar, and a 1u R4 key to use as Caps Lock
- 70 MX or Alps switches
- 70 1N4148 diodes
- Insulated wire for connecting the key matrix to the controller (see matrix/pin diagram in the Miscellaneous folder)
- Solder and soldering iron (for wiring, and for heat-setting the threaded inserts into the support wedges)
- One clip-in plate mounted 7u or 8u stabilizer for the spacebar
- Optional: 70 [1u Amoeba PCBs](https://keeb.io/products/amoeba-single-switch-pcbs)
- Optional: Five decorative top plates, one for each row (AI files for lasercutting in the Plates folder)

### Default Keymap:
<img src="https://github.com/jyuenger/Tierwriter/blob/main/documentation/Default%20Keymap.png" width=300>

## To Do:
- Write build guide
- Port firmware to VIAL
- Design decorative/protective exterior casing
