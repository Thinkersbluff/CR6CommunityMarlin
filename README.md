# Community firmware for the Creality CR-6 3D printer

**This extui branch is configured for the Creality CR-6 SE with stock TFT plus the following modifications:.**
* Converted to Direct-Drive
* Orbiter v1.5 extruder with the Moon stepping motor
* Dragon HF hot end
* 0.9 degree stepping motor on Y-Axis


_For other configurations for the Creality CR-6 printer (like BigTreeTech SKR board and optional BTT TFT v3.0 display - please check the [branches and development](#development-and-compile-it-yourself) section below._

## Downloads

CAUTION: Anyone downloading this customized version of the community firmware does so entirely at their own risk.

Please find official releases of the upstream Community Firmware in the [Releases section](https://github.com/CR6Community/Marlin/releases). 

*Support for the BTT SKR board is available [here](https://damsteen.nl/blog/2020/11/25/how-to-btt-skr-cr6-installation).*
Acquiring the board may, however, be problematic, now that it is out of production.

### Development and compile-it-yourself

There are several example configurations available for convenience. You can find them in the [`config`](./config) directory. Copy the files from the right directory to the root of the repository and you can directly build them if you have the Platform.io plugin installed in Visual Studio code. You will need to set the Platform.io environment to the environment in the file `platformio-environment.txt`.

Examples for the following hardware configurations are currently supported by the upstream repository:

- Creality stock TFT with:
   - Creality v4.5.2 motherboard (CR-6 SE)
   - Creality v4.5.3 motherboard (CR-6 SE and CR-6 MAX) - also supports CR-ERA 1.1.0.3
   - BigTreeTech SKR CR6 (CR-6 SE)
- BigTreeTech SKR CR6 with BigTreeTech TFT v3.0


## Community firmware support & communities

Get in touch with the developers! We [have our own Discord server](https://discord.gg/RKrxYy3Q9N).

The following CR-6 communities exist:

- [Facebook independent CR-6 community](https://www.facebook.com/groups/cr6community)
- [Reddit /r/CR6](https://www.reddit.com/r/CR6/)

Communities hosted by Creality:

- [Official CR-6 user group](https://www.facebook.com/groups/CR6SECR6MAX)
- [Official Creality user group](https://www.facebook.com/groups/creality3dofficial)

Other communities:

- [Reddit /r/3dprinting](https://www.reddit.com/r/3dprinting/)

### General Marlin support

For general Marlin support, please check:

- [Marlin Documentation](http://marlinfw.org) - Official Marlin documentation
- [Marlin Discord](https://discord.gg/n5NJ59y) - Discuss issues with Marlin users and developers
- Facebook Group ["Marlin Firmware"](https://www.facebook.com/groups/1049718498464482/)
- RepRap.org [Marlin Forum](http://forums.reprap.org/list.php?415)
- Facebook Group ["Marlin Firmware for 3D Printers"](https://www.facebook.com/groups/3Dtechtalk/)
- [Marlin Configuration](https://www.youtube.com/results?search_query=marlin+configuration) on YouTube


## Reporting issues

- Submit **bug fixes** as pull requests to the current active default branch (`extui`)of the upstream repository
- Follow the [coding standards](https://marlinfw.org/docs/development/coding_standards.html)
- Please submit your questions and concerns in the [issue tracker](https://github.com/MarlinFirmware/Marlin/issues)

## Credits

The current core CR-6 Community firmware dev team consists of:

 - Sebastiaan Dammann [[@Sebazzz](https://github.com/Sebazzz)] - Netherlands &nbsp; ([Donate](https://www.paypal.com/donate?hosted_button_id=YCH72S6WZQ5X4) ([Profile](https://www.paypal.com/paypalme/sebastiaandammann)) | [Website](https://damsteen.nl))
 - Juan Rodriguez [[@Nushio](https://github.com/Nushio)] - Mexico
 - Romain [[@grobux](https://github.com/grobux)] - France ([Donate](https://www.paypal.com/donate?hosted_button_id=CP2SAW4W9RBT4))
 - Nick Acker [[@nickacker](https://github.com/nickacker)] - USA
 - And more...

We stand on the shoulders of giants. Don't forget to send your love [upstream too](https://github.com/MarlinFirmware/Marlin)!

## License

Marlin and the Creality CR-6 Community Firmware is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
