# CTGPROnDolphin
Repo about running CTGP Revolution on Dolphin Emulator.

## Method 1: Quick and Easy
In the releases tab, find the most recent release and download the save state. Then, open your Mario Kart Wii ISO in Dolphin, and load the save state you downloaded. (This works after installing CTGP-R Channel (covered in method #2)... not sure what happens without it).

## Method 2: Installing It Yourself
To install it yourself:

1. First, you need a different version of dolphin. Clone the Dolphin repo [based on pull request #11183.](https://github.com/dolphin-emu/dolphin/pull/11183). Build it yourself via instructions in the README and wiki.
2. In your new version of Dolphin: go to Config > Advanced, check the box labeled "Enable Write-Back Cache (slow)". This will slow down Dolphin considerably, but it is necessary to install CTGP-R.
3. Install the Wii menu if you have not already: Perform Online System Update > (Your region).
4. Install Homebrew if you have not already: Download a Homebrew WAD, like from [here.](https://github.com/forwarderfactory/hbc-archive/tree/hbc-wads) Install it by going to Tools > Install from WAD...
5. If you have stuff on your virtual SD card -- back it up. Additionally, go to Config > Wii > Convert File to Folder Now if your SD isn't empty. If you skip this step, your SD card will be wiped.
6. Download the CTGP-R zip and extract it into the SD card folder. You can find the location of that folder by going to Config > Wii > SD Sync Folder.
7. Click "Convert Folder into File Now". Dolphin might freeze -- just wait if it does (should take no longer than 30s). **You will need to repeat this step and all subsequent steps if the installation fails at any point.**
8. Boot into the Wii menu: Tools > Load Wii System Menu 4.3U
9. Once booted, go to File > Change disc. Select your Mario Kart Wii ISO.
10. Disable your computer's Internet. (For whatever reason, updating from the Internet didn't work for me.)
11. Go to Homebrew. Load CTGP-R.
12. CTGP-R will initially show a black screen. Wait.
13. Install CTGP-R as normal.
14. Launch the game.
15. On the title screen, create a save state.
16. Stop the emulation.
17. Go to Config > Advanced, uncheck the box labeled "Enable Write-Back Cache (slow)". When you start emulating again, it will be much faster. If you run into problems, you can always turn it back on.

When you want to play CTGP-R:
Load your regular Mario Kart Wii ISO. Then, load the save state which you created in step 15.
