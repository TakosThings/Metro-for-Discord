# Changelog

#### 0.11.0
* Member status is indicated by a coloured border. Unfortunately there isn't a way to determine between if a user is online or in game

#### 0.11.1
* Corrected background in member activity

#### 0.11.2
* New status indicator in account area
* Selected #channel will indicate using the defined accent colour
* Added accent indicators to mute and deafen buttons

#### 0.11.3
* Corrected style name in //meta
* Updated info for accent colours in config section
* Changed selected channel background
* Less gaps between members
* Possible fix for the jumping account box

#### 0.12.0
* Added config options for user popout backgrounds
* Styles user popouts
* Hid the words 'Playing' and 'Streaming' from under users in the members list
* Styled Pinned Messages

#### 0.12.1
* Finish styling some things I missed on pinned messages
* New pinned messages are indicated with a pulsing bottom border (color is determined by --theme-accent)

#### 0.12.2
* TTV, FrankerZ emotes are now set to 16x16

#### 0.12.3
* Visibility improvement for some toggled buttons

#### 0.12.4
* Fix for the members list icon jumping a few px when the button was toggled

#### 0.13.0
* Re-worked chat box
* X now typing shows in a separate box below the chat box
* Styled the "You must be a member for 10 minutes" chat box blocker

#### 0.14.0
* Styled Direct Messages (Will be completed in next version)
* Styled Pinned Messages (broken in [Dicord+20170711](https://blog.discordapp.com/2016-7-11-change-log/))
* Styled Recent Mentions (added in [Discord+20170711](https://blog.discordapp.com/2016-7-11-change-log/))

#### 0.14.1
* Some refinements in the Recent Messages box

#### 0.15.0
* Styled Settings modal

#### 0.15.1
* Fixed style on Pinned Messages and Recent Mentions boxes... *again.*

#### 0.15.2
* Fix: Focused text boxes
* Fix: A sneaky border-radius in the settings modal
* Set correct colours on links within the user settings modal
* Styled buttons
* Some more touch ups on the settings modals

#### 0.16.0
* Style BetterDiscord settings
* Monokai theme for Custom CSS editor

#### 0.17.0
* Styled the following modals
  * Changelog
  * Create voice channel
  * Profile
  * New server
  * Join server
  * Region select

#### 0.18.0
* Rewrite the redundant modal CSS

#### 0.18.1
* Styled checkboxes in channel roles

#### 0.18.2
* Fix chat not autoscrolling correctly when JTV/BTTV emotes are used

#### 0.19.0
* Finished styling in Server Settings Modal.
* Fix: hover colour on the upload button in the chat box
* Fix: colouring of Join or Create server button
* Fix: colouring of Join or Create server boxes
* Fix: Leave Server font color
* Fix: Expanding delete buttons not sizing correctly
* Styled: Tooltips
* Styled: BTTV Emote menu
* Adjusted size of modal header and footers
* Finished server notification settings
* Current Emoji section highlights with Accent colour
* Fuck modals!

#### 0.19.1
* Fix: mis-aligned pinned messages notifier
* Fix: dark mode support
* Styled: day and new message chat dividers

#### 0.19.2
* Fix: Debug modal text colours
* Fix: Hover background in add roles popup
* Fix: Help modal style. It's still a little broken, but I've lost patience with it.
* Styled: Connection info popup

#### 0.19.3
* Finished styling for friends
* Selected server without a custom icon will use the accent colour

#### 0.19.4
* Fix: Spaces aren't allowed in the theme name (Thanks, @Mitchel#5985)

#### 0.19.5
* Fix: Fallback fonts weren't working because I forgot quotes around Segoe UI. (Thanks, @Nirewan#6392)

#### 0.20.0
* Update: Add styling for latest [Discord update](https://blog.discordapp.com/2016-7-28-change-log/)
* Fix: Make new messages divider text normal case
* Fix: Broken style on New group DM pop
* Fix: Members list no longer flashes white while loading
* Fix: Some uncoloured text in Connections settings
* Fix: poor readability for detected games in settings

#### 0.21.0
* Styled: Public Servers list

#### 1.0.0
Everything is done!

#### 1.0.1
* Tidy some comments
* Add contact details at top of css
* Attribution for Monokai theme added to top of css
* Fix: Font applied in `GLOBALS` now uses `--theme-font`

#### 1.0.2
* Shipped with wrong default accent colour

#### 1.1.0
* Added plugin support for [Clock Plugin](https://github.com/Jiiks/BetterDiscordApp/blob/master/Plugins/clock.plugin.js) by Jiiks
* Added plugin support for [CopyCode](https://github.com/Finicalmist/CopyCode/blob/master/copyCode.plugin.js) by Finicalmist

#### 1.2.0
* Added plugin support for [Even Better Repo](https://github.com/IRDeNial/BD-Even-Better-Repo) by DeNial

#### 1.2.1
* Fix: Hide header on Even Better Repo plugins page

#### 1.3.0
* Added update notifier
* Text channels now pulse when a new unread message it received
* Added link for Even Better Repo's repo
* Fix: Incorrect profile modal background
* Fiddle: BTTV etc. emotes margins