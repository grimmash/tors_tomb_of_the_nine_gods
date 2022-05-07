# Using MrPrimate's DDB Muncher
You can use Mr. Primates DDB Muncher via the `D&D Beyond Importer` module to populate the actors in this module.  **You must own the Tomb of Annihilation content in D&D Beyond for this to work!**

These instructions provided as-is!  If you have concerns/questions/etc, you may be able to find me in the Tomb of Annihilation DM Discord.  Or even better, check in on Mr. Primates various channels to see the current status and get any help.  There are a lot of things going on here :).

1. Import and activate Foundry modules:

 - D&D Beyond Importer
 - Tor's Tomb of the Nine Gods


2. Set Up D&D Beyond Importer
  1. Go to `Settings`>`Module Settings`>`D&D Beyond Importer` > `Core Settings`  
  2. Enter your Cobalt Cookie from D&D Beyond.
    - Navigate to D&D Beyond in Chrome (no idea if other browsers work)
    - Hit `F12` to open the console
    - Under the `Application` tab, select `Storage`>`Cookis`>`https://dndbeyond...`
    - In the `Search` box type "cobalt"
    - Copy the entire `cookie value` field into the filed in Foundry's settings menu

  3. Enter you Patreon Key from Mr Primate's Patreon
3. Import the Tor's Tomb of the Nine Gods Scenes into your game so they are present
4. In the `Compendium Tab` you'll need to set up the adventure in the DDB Muncher. You can follow these instructions https://docs.ddb.mrprimate.co.uk/) located halfway down the page labelled "adventure muncher", or try to follow my instructions:
  1. In the `Adventure` tab of the Muncher, select `Generate Adventure Muncher File` for Tomb of Annihilation
  2. Download the Adventure Muncher from Mr. Primate's Patreon. If you’re using Windows, you want the file ending .exe, if you’re using a Mac .dmg, and if you’re using Linux, you have a choice between a deb, rpm or AppImage (stand-alone).
  3. Install the software as is appropriate for your OS.
  4. Run the software. You should get a screen as follows: (see link above)
    - Click the “Load config file” button and browse to the config file you downloaded from within Foundry.
    - Once loaded into Adventure Muncher, you can remove the download. Adventure Muncher stores the config in its own settings folder.
    - You should now select a folder to output the generated adventures and set it with the “Select output location button”.
    - You should now be able to select an adventure to generate. **You need to have access to this content on D&D Beyond.**
    - If you want to generate tokens on scenes (Foundry v8+ only), then tick “Generate actors and tokens?”. Please note that not all scenes have actors placed on them at the moment. This is a community effort, and you can see the current progress at the nice visual display or the boring (but more detailed) spreadsheet.
    - If you wish all the Journal and Table entries to be viewable by players (useful in books such as The Players Handbook), tick this option.
    - Click Generate. It may take a few minutes to generate an adventure, depending on the speed of your computer and internet. If you have problems, see the Troubleshooting section.
  5. Once you generated the adventure, in Foundry in the Muncher, select `Import Generated Adventure` and import the adventure you made

5. Go back to DDB muncher, select `Enhance Third Party Scenes` then select `Tor's Tomb of the Nine Gods`

6. Review each scene and make sure all the tokens and walls are set up the way you want!
