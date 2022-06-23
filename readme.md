# Flashforge 3D Printer - Ultimaker Cura Profiles
Since there is no official Cura profiles for the Flashforge Adventure 3/Monoprice Voxel i decided to compile one myself after gathering info from Flashforge forum and from others attempts posted on GitHub.
### Supported Printers
* Flashforge Adventurer 3 - yes
* Monoprice Voxel (as above)
* Flashforge Dreamer NX - yes
* Flashforge Adventurer 4 - yes

  - There is also support for differnt nozzle sizes for all printers.
## Installation
Everything in the "resources" directory should be copied to the installation path sub-dir /share/ of Ultimaker Cura. Can look something like this "C:\Program Files\Ultimaker Cura 5.0.0\share\cura\resources"

Restart Cura and then simply add a new printer, the Flashforge printers should now be listed as a "non-network printer".
## Usage

After slicing your project, Cura vill save the result as a .gcode file thats not 100% compatible with the Flashforge printers, that prefers a .g file that includes som extra binary information.

So provided in this repository is Flashforge own software cura2ff a windows application that will convert the file to .g.

You can then put the .g file on a usb stick and print as ususal or even upload to Polar Cloud.


## If you like?
Use as you wish... if you feel you want to you can always send me a some 💰 to my ₿TC wallet: 3EFWQTAbgGctrCeLL5nYTS1RrrtnWYrnYA


## If your from Flashforge
Please make even better profiles then mine, and make it part of the official Cura release, without any need for external file converters.

Otherwise your free to recommend these profiles, but i could always use a new and better 3D printer 😍
## Contributing

Contributions are always welcome!



## 🥷About Me / Contact

Swedish Nerd with some mixed skills in programing, development and networking/clustering. Been doing the computer thing for a few decades now.
If you have any feedback, please reach out to me at conny@ankargren.com

// Regards Conny "NinjaAsok" Ankargren