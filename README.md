# Metro for Discord
A custom theme for Discord based on Microsoft's Modern Design Language - 'Metro'.  

Latest version: `3.13.2`

## Download
Get the latest version from the [Releases](https://github.com/TakosThings/Metro-for-Discord/releases/latest) page

## Install
You should follow the relevant install instructions for your platform.  
* [BeautifulDiscord](https://github.com/DTinker/discord-resources/wiki/Installing-Modifications#beautifuldiscord)
* [BetterDiscord](https://i.imgur.com/H7VyWea.png)

## Requirements
* An up to date install of Windows 10 with Segoe UI MDL2 Assets font. 
* English language selected. The theme relies upon English strings to replace icons.

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
`--link` changes the colour of links in chat. The default colour is *Default blue*. Normally you should leave this as default.

**Voice**  
`--voice` changes the colour of the ring which indicates where you are connected to a voice server. The default colour is *Turf green*. Normally you should leave this as default.

## Screenshot
![Preview](https://i.imgur.com/gk3IlYT.png)

This project is not associated with Microsoft, nor Discord.
