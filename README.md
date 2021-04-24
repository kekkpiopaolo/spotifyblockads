[![Build status](https://ci.appveyor.com/api/projects/status/31l6ynm0a1fhr2vs/branch/master?svg=true)](https://ci.appveyor.com/project/mrpond/blockthespot/branch/master)  [![Discord](https://discord.com/api/guilds/807273906872123412/widget.png)](https://discord.gg/p43cusgUPm)

<center>
    <h3 align="center"><a href="https://en.wikipedia.org/wiki/2020_Thai_protests">Support the 2020 Thailand & 2021 Myanmar protests</a></h3>
    <h3 align="center">Help me stop the dictatorship in Thailand and Myanmar!</h3>
    <h3 align="center">Southeast Asia strong together!</h3>
</center>

<center>
    <h1 align="center">BlockTheads</h1>
    <h4 align="center">A multi-purpose adblocker and skip-bypass for the <strong>Windows</strong> Spotify desktop application.</h4>
    <h5 align="center">Please support Spotify by purchasing premium</h5>
    <p align="center">
        <strong>Last updated:</strong> 21 April 2021<br>
        <strong>Last tested version:</strong> 1.1.57.443.ga029a6c4(-a)
    </p> 
</center>

#### Important checks before installing:
0. Update Windows, update Spotify and update BlockTheSpot
1. Go to "Windows Security" -> "Virus & Threat Protection"
2. Click "Allowed threats" -> "Remove all allowed threats"

### Features:
* Blocks all banner/video/audio ads within the app
* Retains friend, vertical video and radio functionality
* Unlocks the skip function for any track  
* Now supports the new Alpha version (New UI)  

:warning: This mod is for the [**Desktop Application**](https://www.spotify.com/download/windows/) of Spotify on Windows only and **not the Microsoft Store version**.

#### Installation/Update:
* Just download and run [BlockTheSpot.bat](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/mrpond/BlockTheSpot/blob/master/BlockTheSpot.bat)
* Enter 'Y' when promoted to swap Alpha UI to Old UI if needed.
or
1. Browse to your Spotify installation folder `%APPDATA%\Spotify`
2. Download `chrome_elf.zip` from [releases](https://github.com/mrpond/BlockTheSpot/releases)
3. Unzip and replace `chrome_elf.dll` and `config.ini` 

#### Uninstall:
* Just run uninstall.bat
or
* Reinstall Spotify 

#### Known Issues:  
* Optional feature "Remove Upgrade Button" will not work with Spicetify, also might have issues with alpha Spotify.  
* It will also have issues with the latest Spotify version where the user avatar will be blank, Check [#83](https://github.com/mrpond/BlockTheSpot/issues/83) for more info.   

#### Note:
* "chrome_elf.dll" gets replaced by the Spotify installer each time it updates, make sure to replace it after an update.  
* Spicetify users have to reapply BlockTheSpot after applying a Spicetify theme.  
* The ad banner may appear if your network uses [Web Proxy Auto-Discovery Protocol](https://en.wikipedia.org/wiki/Web_Proxy_Auto-Discovery_Protocol)
    * Setting `Skip_wpad = 1` in config.ini may help
* For Spotify Premium users, setting `Block_BannerOnly = 1` will only block the banner at home
* If the automatic install/uninstall scripts do not work, please contact [rednek46](https://github.com/rednek46)
* For more support and discussions, join our [Discord server](https://discord.gg/p43cusgUPm) 


