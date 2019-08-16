# Metro for Discord
A custom theme for Discord based on Microsoft's Modern Design Language - 'Metro'.  

Latest version: `3.11.2`

## Download
Get the latest version from the [Releases](https://github.com/TakosThings/Metro-for-Discord/releases) page

## Install
You should follow the relevant install instructions for your platform.  
* [BeautifulDiscord](https://github.com/DTinker/discord-resources/wiki/Installing-Modifications#beautifuldiscord)
* [BetterDiscord](https://i.imgur.com/H7VyWea.png)

## Requirements
This theme utilises the Segoe UI MDL2 Assets font to provide some icons. You may notice missing icons if you are not running Windows 10.

## Configure
### Required
* Discord's dark theme must be selected from the Appearance tab in User Settings.
* BetterDiscord users must also disable the following options;
  * Dark Mode
  * Normalise Classes
  * Public Servers

### Variables
The theme has some variables which can be changed by editing the CSS file

**Accent Colour**  
You can change the accent colour by changing the `--accent` variable at the top of the CSS file. A list of the default colour swatches from the Windows 10 personalisation settings is available on the [MicrosoftDocs/windows-uwp](https://github.com/MicrosoftDocs/windows-uwp/blob/53eb5fbcf125c9b189de37a6afb8b50ccc2a49fe/windows-apps-src/design/style/color.md#windows-accent-colors) repo. The default colour is *Default blue*. Brighter colours work best as your accent colour.

**Link Colour**  
You can change the colour of links in chat by changing the `--link` variable at the top of the CSS file. The default colour is *Default blue*. In general you should leave this as default.

**Voice**  
You can change the colour used to indicate where you are connected to a voice server by modifying the `--voice` variable at the top of the CSS file. The default colour is *Turf green*. In general you shouldn't need to change this.

### Advanced
The following options require a line of CSS to be removed from the CSS file.

**Blocked Messages**  
The 'x Blocked Messages' reminder is hidden by default.

**Welcome Message**  
The 'Welcome to your/the server' message is hidden by default.

## Screenshot
![Preview](https://i.imgur.com/gk3IlYT.png)

This project is not associated with Microsoft, nor Discord.
