This is how it looks like - [url]https://youtu.be/i-c1b6sbzfs[/url]

It is based on an app which can simulate Tap/Touch behavior by finding pixel color so literally it can do almost everything you can with your phone. But as a consequence it is not productive, something like 10~15k /h, comparing with any of the bot on forum which talking directly to api instead of simulating. It can do only what you asked, and give you some supply on the pokeballs for sniping, so say, better than going outside and catch'em all on your own.

How it works:
I pre-set all the locations in fake-gps which it will visit and all the coords where the pokestop is to tap. like us, it will first set the location in fake-gps and then come back to the game. farm pokestop. After that, it will search the screen to match the pixel color with color which pokemons has. once it find it will throw balls and catch it(or flee..). when it spin the pokestop, if there is a sign that your bag is full, it will start clean the bag according to the settings within the file. meanwhile, it can handle most error to make itself running smoothly.

Feature:
a. auto farm predefined pokestops. 
b. auto find and catch pokemon.
c. auto managing your bag.
d. 24/7.

[B]Issues:[/B]
a. it won't catch all the pokemon on screen, say catch about 80%.
b. these predefined pokestops are around where I live, as a result, it will teleport you to Rhodes,.Sydney, which may cause you softbanned, if so, unban youself by spinning the pokestops. 
c. not a real issue but kind of complicated to set up all the stuff.

Requirements: 
a. rooted Android device / Nox.
b. fake gps / lucky patcher / gravitybox / titanium backup 
c. the simulating app/apk is called mobileAnjian. it is in Chinese as I can't find any alternative. it is an identical app comes with Nox but I have no idea how to use that one.

Preparation: (tested on my hyper v machines with Nox so should work for you guys)
a. open Nox setting from top right corner and turn "Root" in "General Tab" to "On"
b. in "Advanced Tab", set "Startup Setting" to "Phone" and "720x1280" , save changes and reboot if it is asked to.
c. login your google account and turn off app auto update with wifi in Play Store.
d. install Lucky patcher and after that, use lucky patcher to install fake gps as system-app
e. install Xposed if you don't have, then GravityBox [KK]
f. install Titanium backup and then copy TitaniumBackup folder to /storage/sdcard0 in Nox
g. use Titanium Backup to restore data for fake-gps and GravityBox
h. use Titanium Backup to restore App and data for mobileAnjian, which has a blue icon and shows some Chinese characters ending with "3.0.1" 
i. copy two .txt files to your Nox shared folder: \mnt\shared\Other
j. check everything above is in working condition.

Good to go:
a. run the blue icon app in chinese.
b. click the blue icon.
c. click pg-nox0723 then click green play button it will minimize itself. (you may have to change the settings on what to keep and what to discard by click the upper right 'edit' button and edit line 21 to ka=Array(0,0,0,0,0,0,0,0) to make it keep everything or line 22 to set the amount.)
d. run the game
e. click the play button to start the macro.
All done.

All files needed can be found here: [url]https://mega.nz/#!mQlBhbxS!mt7dNd_94eBVhHC9sScYPEyymIE22GIr5bxUpaFdjVA[/url]

I understand it is a simple macro but quite long list to configure it to work. Maybe add some features to auto walk instead of predefined locations to make it easy to use while the bot are down, may not intend to maintain it for a long term.

at last, thanks for the developers and all those who contribute to their wonderful work to make it happen.
