# PersonalKiCad

Library setup guide [here](https://github.com/joe-scotto/scottokeebs/blob/main/Extras/ScottoKicad/README.md). Use "Personal" instead of "ScottoKeebs".

A collection of footprints, symbols, and 3D models for building mechanical keyboards with KiCad.

This repo and most of the files were originally collected by [Joe Scotto](https://github.com/joe-scotto).

Because Joe updated/created some of his symbols and footprints with newer versions of KiCad (instead of version 7.0.11), they were no longer compatible with previous versions. Hence, this fork/repo, with most of the footprints and symbols working and complete for version 7.0.11.

I've renamed all the folders, files and the corresponding paths from 'scottokeebs' to 'personal' in order to improve reuseability and individualisation, as 'personal' is more impersonal and easier to remember for oneself than 'scottokeebs'.

# Common grid sizes

-   18x17mm (Choc)
    -   1.00u - X: 18, Y:17
    -   0.50u - X: 9, Y: 8.5
    -   0.25u - X: 4.5, Y: 4.25
-   19.05x19.05 (MX/Alps)
    -   1.00u - X: 19.05, Y: 19.05
    -   0.50u - X: 9.525, Y: 9.525
    -   0.25u - X: 4.7625, Y: 4.7625
    -   0.125u - X: 2.38125, Y: 2.38125

# Common Shortcuts

-   **Add (A)** - Add a footprint or symbol.
-   **Set Origin Point (S)** - Set where everything else will move in relation to.
-   **Move with Reference (])** - Move a footprint with a reference point.
-   **Track Tool (X)** - Place traces
-   **Add Via (V)** - Place a via to run a trace between PCB layers.
-   **Flip (F)** - Switch footprint between back and front of the PCB.

# Resources

Please refer to each library in order to understand the license it uses, most are Creative Commons CC-BY-SA 4.0.

-   [Keyswitch Library](https://github.com/kiswitch/kiswitch/tree/main) - 3D models and footprints for switches, stabilizers, and sockets.
-   [Raspberry Pi Pico](https://github.com/ncarandini/KiCad-RP-Pico) - 3D model, footprint, and symbol.
-   [Arduino Pro Micro](https://github.com/g200kg/kicad-lib-arduino) - Footprint and symbol.
-   [Marbastlib](https://github.com/ebastler/marbastlib) - Symbols.
-   [Kleeb](https://github.com/crides/kleeb) - 3D models, symbols, and footprints.
-   [Keebio](https://github.com/keebio/Keebio-Parts.pretty) - 3D models, footprints, and symbols.

# Credits

-   Original repo/folder - Owner and maintainer is [Joe Scotto](https://github.com/joe-scotto). The forked folder is from his main scottokeebs repo, [ScottoKicad](https://github.com/joe-scotto/scottokeebs/tree/main/Extras/ScottoKicad).
-   nice!nano - Base dimensions and placement by @Knotherface, can be found on GitHub as [Leopere](https://github.com/Leopere).
-   Frood - Footprints and symbols were gathered from [piit79](https://github.com/piit79)'s [Frood](https://github.com/piit79/Frood) repo (GNU General Public License v3.0).

# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/joe-scotto/scottokeebs">ScottoKeebs</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/joe-scotto">Joe Scotto</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0