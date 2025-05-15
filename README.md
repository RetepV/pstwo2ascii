# pstwo2ascii
My rendition of Jim Brain/RETRO Innovations **PS2Encoder**.

The original (copyrighted by Jim Brain and RETRO Innovations) can be found here: https://github.com/go4retro/PS2Encoder.

I decided to make the board USB powered, and add a "real" RS-232 V24 interface. Most vintage computers cannot work with 0V/5V, but need positive and negative voltages. And some old vintage computers output +12V and -12V, and wil very likely blow up the ATMEGA's ports. Lastly, I used an ATMEGA328 instead of an ATMEGA88, just because I have a few of those lying around.

I decided to make it in SMD, to keep the boards small. I took hand-solderability into account as much as possible. Of course the connectors mostly dictate the final size of the board, and t.b.h. I think that if I had used PTH components, the board would not be much larger. But there you go: it's my design and I can do what I want to. ;)

**Note: this is a WIP and has not been tested yet, prototypes have not even been created yet.**

The base design and the software is not mine, but created and copyrighted (2008-2018) by Jim Brain / RETRO Innovations. I took the base design, redesigned it to make a full-fledged board powered by USB and having a real RS-232 V24 interface using a MAX232, and named it **pstwo2ascii**. This board is meant to be used with the firmware of **PS2Encoder**, which can be found here: https://github.com/go4retro/PS2Encoder/tree/master. Big thanks and kudos to Jim Brain for his work!

Please note that **pstwo2ascii** is covered under GPLv3, while **PS2Encoder** is covered under GPLv2. **pstwo2ascii** only applies to the hardware designs that you can find in this repository.

## Licenses

### PS2Encoder

Copyright Jim Brain and RETRO Innovations, 2008-2018

These files are free designs; you can redistribute them and/or modify them under the terms of the GNU General Public License, version 2 as published by the Free Software Foundation.

These files are distributed in the hope that they will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with these files; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

### pstwo2ascii

Copyright Sporos Tech, Peter de Vroomen, 2025

**pstwo2ascii** is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

**pstwo2ascii** is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with **pstwo2ascii**. If not, see <https://www.gnu.org/licenses/>. 
