# Blocktopograph

## ![author](https://github.com/Templarian/MaterialDesign/blob/master/svg/account.svg) Authors & Contributors
**Latest Releases:**
- Etanarvazac (Lead)

**Past Versions:**
- Proto Lambda (User requested to not be linked.): Original
- [@MithrilMania](https://github.com/MithrilMania)
- [@flagmaggot](https://github.com/flagmaggot)
- [@oO0oO0oO0o0o00](https://github.com/oO0oO0oO0o0o00): Up to version 1.9.5

**Other Contributors / Variations:**
(Will be added upon their releases of a working, stable build.)

This fork may be the only one to soon support MC 1.18 and Android 12.

## ![update](https://github.com/Templarian/MaterialDesign/blob/master/svg/update.svg) Updates
This project is quite old and hopefully can be updated to the current versions of Android and MCPE.

**To Do:**
1. Gain access to the new world save location. (/Android/Data/com.mojang.minecraftpe/files/games/com.mojang)
2. Update Map to read 1.18+ worlds.
3. Update NBT editor to account for 1.18 values.

## Planned Feature & Bucket List
**1-Stop-Shop:** Basically making this a powerful tool for players and content creaters alike. To do this, many additions will be made:
1. Add-On Editor: Adding a powerful editor for making resource packs and behaviours alike. This will have two varients. One being a simple GUI to build from, the other for those who wish to dig deep in code.
2. Full Backup & Restore: Make it easier to ensure your content isn't lost. This is planned to have ties with automatic cliud sync in Google Drive.
3. Guides: For the new players out there, guides eill not only be added, but a floating window will be too. Allowing you to be use it while actively playing in your worlds.

**Additional Features:** It'd be real dumb to just check off the bucket list. Improvements can be made everywhere.
1. Themes: Yes, the ability to go between light and dark mode and changing the classic green.
2. Advanced NBT Editor: Don't know the ID's? No problem. One of the planned improvements is to enable players to choose or view an item without knowing it's ID. Viewer would give the name (e.g.: minecraft:wool), the varient and value (e.g.: Black, 15) and a image of the block. Everything gets broken down making things easy.
3. World List/Detailed View: More info including the world image will be added.
4. Custom Worlds: And not just just flat worlds. You will gain the Bedrock equivalent of Java's custom world creation allowing you to tweak every aspect of it.

**Bucket List:**
First thing's first, cleanup and fixing what's broken.
1. Got to have the ability to access the new file location. Whether that's direct modifications, or moving worlds to a temporary folder and zipping it in a .mcworld file for importing. One of the two must happen.
2. Map needs an overhaul. Coloration, enity appearance, etc. It's all got to get updated.
3. NBT Editor also needs an overhaul. Tree view has it's benifits, but this is currently a bit sloppy. So it needs cleaned up.
4. Enity views (including players). An effort will be made to decode player names for multiplayer worlds. If not, a nicknaming ability will be added.

## Translations/Pull Requests
Until 1.18 is supported and on Android 12+, translations are put on hold. Pull requests are accepted if it is deemed to help accomplish the goals outlined above.

## ![download](https://github.com/Templarian/MaterialDesign/blob/master/svg/download.svg) Downloads
Latest version: 1.9.5

**Google Play:** [Unavailable: This might stay this way due to Google's new policies.]

**Aptoide:** [Unavailable: This will be the new download location upon release of a stable build.]

Original Screenshots:
<img src="arts/scr02.png" alt="Error loading screenshot." width="320"/>
<img src="arts/scr03.png" alt="Error loading screenshot" width="320"/>

## ![build](https://github.com/Templarian/MaterialDesign/blob/master/svg/hammer-wrench.svg) Build your own version
**Android Studio:**
1. Clone project: `File -> New -> Project from Version Control -> Git`
2. Install the missing SDK components (which Android Studio should give you the Auto-Fix options).

**Your Android Device:**
1. Fork this project from your web browser (make sure "Desktop Site" is enabled)
2. Create a Persional Access Token on GitHub `Tap picture -> Settings -> Developer Settings -> Personal Access Token` (You will need to copy the key you are given. You'll only see it once at the the time of creation.)
3. Download Acode from Google Play. [Download](https://play.google.com/store/apps/details?id=com.foxdebug.acode)
4. Tap on 3 dots in top-right and then on GitHub. This is where you need to provide the key copied from step 2.
5. Upon completion, anytime you tap on that menu option, your GitHub profile should be displayed. You now only need to navigate to your fork (repo) of this project. Saving any opened file in Acode will automatically commit the change in GitHub.

## A Bit of History
The original Google Play version was managed by [@MithrilMania](https://github.com/MithrilMania) which means the release-signing keys are NOT available. You would need to build it as a debug version or sign it with your own keys. There is no guarentee that version will be updated. However, there is a chance that any significant and well-written feature additions or fixes will make it into that build.

**Questions?** Proto said they do not wish to be bothered about this project anymore. So if you have any questions or genetal feedback, please use the issue tracker.

## Wiki
Reasonable wiki-suggestions are welcome; comments should be sufficient for most parts of this project.

## License Information
**License:** AGPL v.3

**Direct consequences:** All public distributed changes in the source-code are required to be disclosed, including their source-code.

*Full license can be found in the [**LICENSE**](LICENSE) file in the root folder of this repository.*

**Attributions Required:**
You must have a attribution to every significant contributor to this project. This includes but is not limited to:
*Proto Lambda:* The original author.
*MithrilMania:* The maintainer of the original (and official) app.
*Others:* Anyone else who made a contribution. A full list can be found in [CONTRIBUTORS.md](CONTRIBUTORS.md) out of respect for their work on this software

*License-head:*

    Blocktopograph -- Blocktopograph is a fan-made app for MCPE, it includes a top-down world viewer and a NBT editor.
    Copyright (C) 2016 Proto Lambda

    This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.

## Final Notes
**Contributions:**
- All Contributions are always welcome. Any large contribution will be noted in [CONTRIBUTORS.md](CONTRIBUTORS.md).
- Many files won't be updated straight away. I am working on much of it offline. Be patient, please.