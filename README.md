comp_module
===========

An ENL 3.2.0 based module system containing all the CoMP maps

Current order of CoMP maps (ENL mod 3.2.0 correspondence)

* Solace (mixed, stable) -- Custom Map 1
* Dry Valley (Mixed, Stable) -- Custom Map 2
* Verloren (Closed, Stable) -- Custom Map 3
* Open Plain (Open, Testing) -- Custom Map 4
* Oasis (Open, Testing) -- Custom Map 5
* Swamp (Open, Unstable) -- Custom Map 6
* Delta (Open, Unstable) -- Custom Map 7
* Liberty (Mixed, Unstable) -- Custom Map 8
* Snoop's Exile Island (Mixed, Unstable) -- Custom Map 9
* Haranaer (Open, Unstable) -- Custom Map 10
* The Wold (Open, Unstable) -- Custom Map 11
* Urabhaya (Closed, Unstable) -- Custom Map 12
* Rock Port (Mixed, Unstable) -- Custom Map 13
* River Valley (Mixed, Unstable) -- Custom Map 14
* Shariz Village (Closed, Unstable) -- Custom Map 15
* Old Rhodok Stronghold (Closed, Unstable) -- Custom Map 16
* The Abbey (Mixed, Unstable) -- Custom Map 17
* Low Born (Closed, Unstable) -- Custom Map 18

Build instructions
==================
1) Download the latest module snapshot from https://github.com/wbkiss/comp_module/archive/master.zip
2) Unzip the file
3a) If you are using Windows, run build_module.bat. Note you will need Python 2.7 installed (see standard Warband Module System build instructions)
3b) If you are using *nix, run build.sh. You will also need Python 2.7 installed.
4) Once the build script has finished, a directory called "dist" will appear. It contains a complete Native and ENL compatible module
5) Copy the contents of "dist" to the Modules/Native/ directory on your server. You don't have to have a module there prior to copying.
6) Optionally, you can copy the contents of "dist" to the Modules/Native/ directory on your client machine so that you can see the correct map names in the admin console.

Once again, the module is not intended for wide deployments as it changes often, but you're welcome to use it if that's what you want.