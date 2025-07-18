# flipper-stuff
Repo for Flipper Zero stuff, including BadUSB attempts

Initial offering is:  
**android-brute** - Automated password enterer to run against an Android tablet in lockdown mode. It is written to run on a Flipper Zero using BadUSB. Currently password list needs to be entered manually and there is no feedback to confirm if the tablet unlocks so it needs to be watched. Has been tested only on Samsung SM-T820.

### Current method of use:  
1. Attach Flipper to tablet
2. Back tablet out of "On lockdown" screen
3. Wait for tablet to sleep
4. Run script in BadUSB
