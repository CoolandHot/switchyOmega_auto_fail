# switchyOmega_auto_fail
My Proxy SwitchyOmega in Chrome suddenly fail only in auto switch mode for no reason (neither is the Chrome version nor the SwitchyOmega plugin version updated). I was using the winXray for the proxy. However, v2rayN was also tested with the same outcome.

## symptoms
### in Chrome
Profiles that works:

[x] [Direct]
[x] [System Proxy]
[x] Proxy Profile
[] Switch Profile
[] PAC Profile

Besides, the system level PAC mode in winXray was not working, either. 

### in Firefox
Works as usual.

## Attemps
1. fail: reinstall Chrome (I always extract the Chrome with winRAR without installation, to keep the system clean. **This is the sticking point!**)
2. fail: reinstall SwitchyOmega, add a simple proxy profile for test.
3. fail: recover the OS, reinstall the OS
4. **success**: download an older version chrome (here I only tried 77.0.3865.90_x86.exe. From [landian CDN](https://dl.lancdn.com/landian/soft/chrome/m/)), I install by double-click the exe file this time (because this version doesn't support extraction with winRAR), and install the SwitchyOmega plugin. It worked this time!!! And my newer version Chrome (it was kept all the time) work as well! Even after I uninstall the older version one which I installed just now. 

I think newer version will also work, the only requirement is to install Chrome with double-click on the exe file. 
