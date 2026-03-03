# TCBM2SD 44-pin
TCBM2SD is a CBM 1551 paddle replacement and/or mass storage device using an SD card interfacing with the Commodore C16/116/Plus4 simulating a TCBM bus 1551 disk drive.

![Board](https://raw.githubusercontent.com/SukkoPera/TCBM2SD/master/img/render-top.png)

## Summary
This is a 44-pin variant of [the original project by Maciej 'YTM/Elysium' Witkowiak](https://github.com/ytmytm/plus4-tcbm2sd).

This version is still aimed at the C16/C116/Plus4 and it **requires** the usage of a [Plus4MultiExpander](https://github.com/SukkoPera/Plus4MultiExpander) or something similar. It is NOT compatible with the C64/C128.

Isn't Open Hardware great?

## Usage
This variant of the board requires the FPGA to be flashed with the JED file from this project. The corresponding sources are available in the [hdl](hdl/) directory.

Apart from that, please refer to [the original project](https://github.com/ytmytm/plus4-tcbm2sd) for documentation, instructions, etc.

## Releases
If you want to get this board produced, you are recommended to get [the latest release](https://github.com/SukkoPera/TCBM2SD/releases) rather than the current git version, as the latter might be under development and is not guaranteed to be working.

Every release is accompanied by its Bill Of Materials (BOM) file and any relevant notes about it, which you are recommended to read carefully.

## License
TCBM2SD is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

This documentation is distributed *as is* and WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties OF MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.


## Thanks
- Thanks to Maciej for his amazing work and support.
- 3D model of Arduino Pro Micro by [Toby](https://grabcad.com/library/arduino-pro-mini-5v-16mhz-1).
