# Changelog
Newest Changes are at the top

#### 1.15.0
* **Repo** (1)
  * Updated CONTRIBUTING.md with info for plugins
* **Enhancements** (2)
  * Added support for BetterDiscord plugins
  * Added support for MemberCount (Arashiryuu) - Provided in #183 by @AHIRA3000

#### 3.14.19
* **Enhancements** (1)
  * Misc improvements in User Settings
* **Fixes** (4)
  * Change colour of subheaders in User Settings to improve legibility
  * Change colour of Log Out item in User Settings to improve legibility
  * Fix gap appearing when no scrollbar was needed
  * Fix channels

#### 3.14.18
* **Fixes** (3)
  * 'Update Ready' toolbar icon not appearing
  * Guilds folder group height
  * Update create new server modal

#### 3.14.17
* **Fixes** (1)
  * Client mute/deafen buttons visible when disconnected

#### 3.14.16
* **Fixes** (2)
  * Missing client mute/deafen buttons
  * Position of screen share buttons

#### π
* **Fixes** (3)
  * Re-enable spinner on loading media (video/images)
  * Fix problems when jumping to messages from search/pinned/mentions
  * Update search results classes

#### 3.14.14
* **Repo** (3)
  * `dist` directory has been removed. Download updates from [releases](https://github.com/TakosThings/Metro-for-Discord/releases/latest).
  * Rewrite of wiki pages
  * Updated README
* **Fixes** (5)
  * Chat scrollbar
  * Friends list scrollbar appearing when not needed
  * New message bars
  * Chat loading placeholders changed to display a simple indeterminate loading bar
  * Reaction emoji picker background

#### 3.14.13
* **Fixes** (4)
  * Change colour of channel categories so they look less like unread channels
  * Various fixes to Group DM popout
  * Server discovery menu items heights to match guilds
  * Missing Server Settings sidebar icons

#### 3.14.12
* **Fixes** (1)
  * Connecting screen

#### 3.14.11
* **Fixes** (2)
  * Missing Server Settings sidebar icons
  * 'x is typing...' alignment

#### 3.14.10
* **Fixes** (2)
  * Missing letter in class for new messages bar
  * Missing `!important`s for avatar size

#### 3.14.9
* **Fixes** (5)
  * Guilds avatar is now the same size as other icons in the list
  * Home conversation list will only show a scrollbar when required
  * Fix width of new messages bars to compensate for scrollbar, added some border-radius
  * Fix width of chat box to compensate for scrollbar
  * Remove a crafty scrollbar hidden in the chatbox (this fixes the Emoji button not attaching to the right side of the chatbox correctly)

#### 3.14.8
* **Tidy Up** (1)
  * Remove unused scrollbar CSS for old Emoji Picker
* **Fixes** (4)
  * Members list background
  * Acrylic overlay was slightly too narrow when viewing User Setttings
  * Emoji picker
  * Home conversation list background

#### 3.14.7
* **Fixes** (5)
  * Update Inbox toolbar button icon
  * Update Inbox and Recent Mentions popout
  * Some modal footers had wrong coloured footer
  * User popout body had wrong background colour
  * Update Search Results pane classes

#### 3.14.6
* **Fixes** (1)
  * Remove `span` from reset

#### 3.14.5
* **Enhancements** (1)
  * Further improvement for low-end PCs
    * [Wiki](https://github.com/TakosThings/Metro-for-Discord/wiki/Acrylic) has been updated with new changes
    * Default acrylic background has been changed
    * Acrylic blur effects are disabled by default. You will need to edit some options in the CSS file to enable blur for your own background. Check the wiki page for more info.
    * Added an option to turn off the UI scale transition effect when opening User/Server/Channel Settings
* **Fixes** (2)
  * Font in chatbox will change to monospace when editing code
  * Chatbox code header

#### 3.14.4
* **Enhancements** (2)
  * Re-write for updated emoji picker
  * Re-write for updated Server Discovery
* **Fixes** (9)
  * User popout inputs had incorrect border widths
  * User modal textarea had incorrect border width
  * User modal pivot selected item had incorrect border colour
  * Link to Discord support site was not hidden in toolbar
  * Implemented a hack to stop the Group DM popout opening halfway off the screen when on the Home/Friends screen
  * A speculative fix to improve performance ~~for people running Pentium 4 CPUs~~
  * Oversized tooltips
  * Context menu
  * Slider grabber position
* **Notes** (2)
  * BetterDiscord: Favourite TTV emotes cannot be accessed. Refer to #156
  * Camera/Screen Share buttons should now be visible when connected to a voice channel. You will find them just above the *Microphone Mute* button. Note that these buttons are smaller than normal as this is intened to be a temporary implementation.

#### 3.14.3
* **Enhancements** (2)
  * Reduce sizes of some icons in the guilds and channel list to match to other icons
  * Add icon for Noise Suppression button in RTC controls
* **Fixes** (3)
  * Emoji picker search box had incorrectly sized borders
  * Emoji picker Nitro promo overlay
  * Emoji picker No Results text
* **Known Issues** (1)
  * The Noise Suppression button icon may disappear when the Krisp popout is open. This is Discord's fault.

#### 3.14.2
* **Fixes** (2)
  * Recent Mentions button missing icon
  * Recent Mentions popout position

#### 3.14.1a
* Only backend changes, no updates

#### 3.14.1
* **Enhancements** (3)
  * You may now click *through* the toast which appears when the theme is loaded
  * BetterDiscord User Settings sidebar should now look closer to the rest of the sidebar
  * Updated tooltip appearance
* **Fixes** (4)
  * Server discovery input out of vertical alignment
  * Server discovery card header images had too large bottom margin
  * Guild group folder container background height would be much longer than necessary
  * User settings log out menu item hover background

#### 3.14.0
* **Clean up** (7)
  * Renamed `/src/components/loadscreen/` to `/src/components/loadscreens/`
  * Moved `/src/components/core/_status_circle.scss` to `/src/components/misc/_status_circle.scss`
  * Deleted `/src/components/notices/_light_mode.scss`
  * Reorganised `beautifuldiscord.scss` and `betterdiscord.scss`
  * Delete `/src/components/popout/_game_preview.scss`
  * Delete `/src/components/notices/_bd_blue.scss`
  * Delete `/src/components/notices/_rmenu_.scss`
* **Enhancements** (4)
  * Accent colour format has changed. See the [wiki](https://github.com/TakosThings/Metro-for-Discord/wiki/Theme-Config) for more info
  * Acrylic. See [wiki](https://github.com/TakosThings/Metro-for-Discord/wiki/Acrylic) for info on customisation
  * Adjusted sizing of indicator pills for guilds, channels, and mentioned messages
  * Scrollbar colours have been updated, and now also respond to additional states
* **Fixes** (10)
  * Some thin style scrollbars had wrong colours
  * Fix language warning not displaying
  * Removed drop shadow from under chat toolbar
  * Links in channel topics not displaying
  * Some missing icons for new menu options in Server Settings
  * Missing channel mute icon in toolbar
  * RTC return to voice channel button floating off position when connected to voice call
  * Mute/Deafen button icons not changing state when toggling
  * Some fixes for conversation list
  * Connecting screen status text

#### 3.13.4
* **Enhancements** (1)
  * Guild voice indicator
* **Fixes** (6)
  * Some tweaks and fixes to channels pane
    * Fixed channel category roots having no hover state
    * Channel category root chevron icons being incorrectly sized, and positioned
    * Channels should now disappear off the bottom less often
    * Clients in a voice channel having no hover state
  * Mention count badge style applying to 'Live' indicator in channels pane

#### 3.13.2
* **Updates** (2)
  * The option for removing the "welcome to the server" message has been removed. The help tips normally provided are removed by default now.
  * The option for removing 'x blocked messages' from chat has been removed.
* **Fixes** (8)
  * Chat mention indicator was incorrect size when not part of the first message in a group
  * Some sizing and position changes to Cosy chat
  * Loading screen status font-weight was too bold
  * Loading screen Twitter and Status Page links
  * Server settings Audit Log had wrong background-color
  * "X is typing" did not move with the chatbox height when typing a multi-line message
  * "Welcome to the server" message
  * 'New' message divider position would break in some scenarios

#### 3.13.1
* **Fixes** (6)
  * Speculative fix for Update Available button having no icon
  * Chat message mention indicator sizing
  * Reduce gap between the last message and top of new day line
  * File filename under icon while uploading a file
  * uploading progress bar
  * Channel group collapse icon faded on one side

#### 3.13.0
* **Clean up** (1)
 * Remove `/popout/_chat_options.scss`, now unused
* **Enhancements** (5)
  * Move theme version number in User Settings from bottom right to Discord's version no. under the logout button
  * Added border lines back to cosy and compact chat modes to assist with chat legibility
  * Changed emoji picker category icons to MDL2
  * Remove Nitro link from Friends conversation list as clicking it breaks the client until restart
  * Some minor style changes to the members list
* **Fixes** (17)
  * Chatbox
  * Remove chat message hover state
  * Decrease font-weight of chat usernames
  * Fix alignment of new chat options
  * Some User Settings sidebar menu options had wrong icons
  * Added bottom margin to increase gap between chatbox and last message
  * Increased left padding on toolbar channel name
  * Many sizing and position fixes for chat
  * Create server modal
  * Remove some duplicate CSS related to badges
  * Fix compact and cosy chat indenting
  * Friends table
  * Chat scrollbars showing both arrow buttons
  * Server region select modal background colour
  * Chat file attachments
  * Recent mentions popout
  * Remove channel toolbar topic font-weight

#### 3.12.11
* **Fixes** (1)
  * Missing or wrong icons for User Settings sidebar menu options

#### 3.12.10
* **Fixes** (3)
 * Upload modal unthemed
 * Missing icon for cancel friend request button
 * Chatbox scrolling issues

#### 3.12.9
* **Fixes** (2)
  * Update rolled classes on chatbox
  * Edit chat message was not themed

#### 3.12.8
* **Fixes** (1)
  * Additional Streaming icons in RTC controls

#### 3.12.7
* **Fixes** (1)
  * Chatbox upload button could not be clicked

#### 3.12.6
* **Fixes** (3)
  * Don't use Imgur for replacing Spotify icon
  * Chatbox had reverted to default style
  * Toolbar icons were doubled

#### 3.12.5
* **Fixes** (5)
  * Chatbox border-top did not indicate focus
  * Chatbox placeholder text colour
  * Chatbox upload button could not be clicked
  * Chatbox Emoji picker clipping over top border when hovered
  * Go live button icons in Activity box

#### 3.12.4
* **Fixes** (1)
  * Oversized Pinned Messages toolbar button icon

#### 3.12.3
* **Enhancements** (2)
  * Rewrite of chatbox SCSS. This may allow BetterDiscord plugins to utilise the `buttonContainer`, however this is untested and will likely cause a problem with the top border which indicates when the textarea is focused.
  * Added a bottom border to emoji picker categories
* **Fixes** (18)
  * Emoji picker category tabs icons were repeating XY
  * Return to RTC channel shortcut had wrong hover background colour
  * Emoji picker info bar had default background-color
  * Embedded content in chat reverted to default
  * Codeblock headers showed extra attributes
  * Codeblock header was still visible when no language had been defined by the user
  * Remove 'User is typing...' dots animation
  * 'User is typing...' position to align with right edge of chat box
  * Chat reactions were unthemed
  * Chat timestamp text colour
  * User popout can no longer be easily forced to display at right side of window, will now open with default behaviour
  * User Settings menu had wrong icons on some options, caused by a new option being added
  * Changed Boost status menu icon in Server settings to match User Settings
  * Emoji picker diversity selector icon size was clipping outside of button
  * Some icons missing from toolbars
  * Pinned/Recent messages popouts leaving a gap between toolbar and popout
  * Profile modal username line-height
  * Create instant invite modal search, and friends list

#### 3.12.2
* **Fixes** (6)
  * Emoji floating under channel topic in toolbar
  * User popouts opening in wrong position
  * Some bottom margins, and hover background-colour in context menus
  * Hide empty item groups in context menu (fixes the double horizontal line in a few context menus eg. guild)
  * Speculative fix for context menu opening under the app titlebar
  * No icon displayed when game streaming is not enabled in that server

#### 3.12.1
* **Fixes** (1)
  * Recent Mentions/Pinned Messages background-color

#### 3.12.0
* **Repo** (5)
  * Themes will now be released through the Releases page
  * Updated download instructions
  * Updated explanations for Variables
  * Update requirements for Windows 10
  * Added requirement for English to be selected language
* **Clean-Up** (1)
  * `/popout/_status_changer.scss` and `/popout/_server_menu.scss` were deleted and combined into `/popout/_channels_menu.scss`
* **Enhancements** (4)
  * Themed 'Go Live' box, and fix it from displacing audio controls
  * Added a warning banner if English or Simplified English is not selected
  * Go Live modal
  * Streaming popout
* **Fixes** (12)
  * Updated Guilds after it was broken in a Discord update
  * Updated Channels after it was broken in a Discord update
  * Muted channel categories will now be coloured red
  * Recent Mentions and Pinned Messages popouts opened 10px too low
  * New Group DM popout opened in wrong position
  * Updated Friends tab after it was broken in a Discord update
  * Load more messages chat button
  * Status changer
  * Context Menu
  * Hover state on members list
  * User/Server/Channel Settings after it was broken in a Discord update
  * Change 'Start Voice Call' icon in Friends table to improve backwards compatibility

#### 3.11.2
* **Fixes** (1)
  * This update changes the *Start Voice Call* icon which could be missing for some users

#### 3.11.1
* **Fixes** (3)
  * Bot tag in user profile popout
  * User avatar sizing in guilds list
  * User status colours

#### 3.11.0
* **Clean-Up** (9)
  * Remove `/core/_userstyle_options.scss` - Unused
  * Remove `/home/games` - Out of scope
  * Rename `/modal/_deprecated_new_server.scss` to `/modal/_new_server.scss`
  * Remove `/primary/members/_loading.scss` - Unused
  * Tidy `/vendor/_hljs_monokai.scss`
  * Clean `/icons/_core.scss`
  * Rename `/modal/_new_modal.scss` to `/modal/_modal.scss` - No longer 'new', implied other function
  * Tidy `/ui/_scrollbar.scss` - Remove old and obsolete classes
  * Remove `/home/friends/_search.scss` - Unused, redundant
* **Enhancements** (12)
  * Remove guild level icon. 'Official' or 'partnered' sever icons will still be shown
  * Remove background from server name menu to expose the server banner
  * Set more aggressive gradient on server banner so it blends with our background-color
  * Server discovery
  * Update Add Friend page
  * Add/Join server modal
  * Added variable for Segoe UI MDL2 Assets font
  * Added icons for menu items in Client/Server/Channel settings
  * Rewrite forms and inputs, and moved to own SCSS files
  * Convert to use MDL icons in most places
  * New profile modal
  * Removed option to hide/show friends online count - counter doesn't exist anymore
* **Fixes** (15)
  * Status circles will now use theme status colours
  * Remove borders or box shadows from status circles
  * Emoji picker search
  * Show selected menu item pill in client/server settings
  * Unmute and Undeafen buttons still appeared when not connected to a voice channel
  * No error message was displayed when chatbox was disabled because user required phone verification
  * Remove tutorial from Quickswitcher modal
  * Account/RTC reverted to default
  * Remove border-radius from server dropdown
  * Fix positioning of status picker popout
  * Remove last separator from status picker popout
  * Instant Invite modal reverted some style to default
  * Use font variable for Connecting screen status text
  * Invite modal
  * Auto complete modal

#### 3.10.10
* **Fixes** (1)
  * Update RTC button classes

#### 3.10.9
* **Enhancements** (1)
  * Add friends to group DM popout
* **Fixes** (5)
  * Improve visibility of unread channels
  * Improve visibility of unread guilds
  * Remove guild icons/abbreviations 'bobbing' effect when in `:active` state
  * User popout in wrong position when opened from voice channel user
  * Speculative fix for context menu clipping under titlebar if viewport is too small

#### 3.10.8
* **Enhancements** (1)
  * Make connected voice and selected text channel icons use accent colour
* **Fixes** (2)
 * Remove border radius on channels list
 * Private voice channels had hash symbol instead of voice icon

#### 3.10.7
* **Enhancements** (1)
  * Remove unneeded header in Direct Messages list
* **Fixes** (2)
  * Guilds, Channels list reverted to default style
  * Toolbars reverted to default style
* **Current Issues** (2)
  * Server discovery button can't be removed without leaving a blank position in the Guilds list. It will stay for now, but the server discovery page will not be themed.
  * Add server button cannot be fixed to bottom of guilds list as it was previously.

#### 3.10.6
* **Fixes** (1)
  * Add server button position

#### 3.10.5
* **Fixes** (3)
  * 'Add Server' tooltip appearing out of place
  * Remove server discovery icon
  * Add background state to user avatar in account area

#### 3.10.4
* **Fixes** (1)
  * Remove bottom margin on add guild button

#### 3.10.3
* **Enhancements** (2)
  * Add hover state to 'return to connected voice channel' button in RTC
  * Adjust channel names colour
* **Fixes** (2)
  * Max capacity voice channel counter
  * Rewrite guilds 💢
* **Background Stuff** (1)
  * Clean-up of `/src/icons/_core.scss` file

#### 3.10.2
* **Enhancements** (10)
  * Removed help button from toolbar
  * Removed version info from below account box. This info will now be shown in a toast at theme load, it is also shown in User Settings
  * Redesign guilds list
  * Redesign accounts box
  * Redesign RTC box
  * Remove server discovery button
  * Spoilers
  * Changed the variable name of `guildvoice` to `voice`
  * Changed default color of `voice` variable to *Turf green* (from *Sport green*) to improve contrast
  * Re-write channels CSS
* **Fixes** (5)
  * Remove favourite button from GIFs (this was supposed to have been removed in `3.10.0`)
  * Remove ellipsis animation from 'X is typing...' text
  * Theme will no longer be applied to Account, RTC, or Settings button if Dark Mode is not enabled
  * Enable dark mode warning banner not displaying
  * Remove border-radius from embedded images, videos
* **Notes** (3)
  * The usage of Accent colours in the guild and channels lists has changed. Previously the Accent colour was used to indicate a guild or channel had unread messages. Now the Accent colour will indicate your currently selected guild or channel. This is to maintain consistency with how Accent colours are used.
  * Microphone and speaker controls are now hidden when you are not connected to a voice server
  * The `voice` CSS variable colour is now used to indicate where you are connected to a voice channel. The default colour is *Turf Green* to match your PTT lamp.

#### 3.10.1
* **Enhancements** (1)
  * Increased spacing between buttons and the search bar when search is active
* **Fixes** (4)
  * Remove border on status indicator in account area
  * DMs avatar size in guilds list
  * Search bar clear icon not visible when search bar is active
  * 'Search for' in search popout had incorrect background colour

#### 3.10.0
* **Housekeeping** (5)
  * Userstyle will no longer be updated. Related `/dist/` and `/src` files have been deleted.
  * *Metro for Discord* Userstyles.org entry has been archived.
  * A CONTRIBUTING.md file will be introduced shortly after this release. This version will cover the scope of the project. Details on development of the theme will come later.
  * Delete `/src/components/modal/_deprecated_help.scss`, as Help modal has been removed
  * Delete `/src/components/core/_font.scss`, as it was marked for deletion in v`3.9.1`
* **Enhancements** (4)
  * Channel notices have been removed
  * Superfluous *Gift Nitro* and *GIF* buttons have been removed from the chatbox. These features can still be accessed via the User Settings and `/tenor` or `/giphy` commands respectively
  * 'Press CTRL+K to Search' help text has now been removed
  * Rewrite search results pane
* **Fixes** (10)
  * Update @ and # mentions in recent mentions popout
  * Fix message preview in the Delete Message modal
  * Chatbox autocomplete
  * ~~Un-fix emoji picker search bar (what even, Discord?)~~ Never mind, Re-fix the un-fix of the fix
  * Update NSFW channel warning class
  * Update chat scrollbar class
  * Emoji picker no results found
  * A '👌' in Emoji picker skin tone selector was overflowing
  * Update Friends list classes
  * Update some classes in Friends conversation list

#### 3.9.14
* **Enhancements** (1)
  * 'Mark as read' option removed from context menu if it is disabled
* **Fixes** (3)
  * Search popout out of position
  * Incorrect CSS being applied to badge in friends list
  * Call toolbar not themed

#### 3.9.13 (1)
* **Enhancements**
  * Revert a previous commit that changed the functionality of the search bar. The required class for this feature was returned
* **Fixes** (1)
  * Update settings classes

#### 3.9.12
* **Changes** (1)
  * Search bar will no longer collapse when not in use due to a change in functionality
* **Fixes** (2)
  * Search popout
  * Chat username font weights

#### 3.9.11
* **Enhancements** (3)
  * Rewrite invite modal
  * Listen along box in channels. *Provided by 'Kinky'*
  * Rewrite Home conversation list
* **Fixes** (3)
  * Offline guild
  * Update classes of help modal
  * Activity tab header bar

#### 3.9.10
* **Fixes** (1)
  * Update welcome message class in options section
  * (Userstyle only) Add placeholder for hiding friends online option
  * Revert a previous commit that updated the class of the eyeglass icon in the search bar because the class was reverted

#### 3.9.9
* **Fixes** (1)
  * Update chat classes

#### 3.9.8
* **Enhancements** (3)
  * Adjust sizing of RTC info/disconnect buttons to match mic/speakers mute buttons
  * Add hover state to RTC info/disconnect buttons
  * Re-write emoji picker. This should fix the jiggling bug.
* **Fixes** (3)
  * Voice disconnect button
  * Remove empty state image from games tab
  * Remove scrollbar from games tab jumbotron

#### 3.9.7
* **Enhancements** (1)
  * The language bar on codeblocks will now be hidden if no language is set by the poster
* **Fixes** (9)
  * Remove search bar from friends list
  * Remove extra eyeglass icon from toolbar
  * Update guilds list
  * Update badges classes
  * Update hide online users count class in user options
  * Add right padding to Friends tab when badge is present
  * Remove inactive scrollbar from codeblocks
  * Edit message emoji button icon
  * Remove setting padding to 0 in the Home > Games screen

#### 3.9.6
* **Fixes** (1)
  * Revert Games/Friends tabs to list items

#### 3.9.5
* **Fixes** (1)
  * Add cases to hide 'User Settings' tooltip if zoom level is set above or below default

#### 3.9.4
* **Enhancements** (1)
  * Re-write keyboard shortcuts modal
* **Fixes** (9)
  * Update RTC class
  * Update selector of 'Open original' link in lightbox
  * Update chat classes
  * Update recent mentions classes
  * Search popout out of position
  * Update chat options class
  * Userstyle not generating
  * Keybinds not themed
  * Create instant invite modal class


#### 3.9.3
* **Enhancements** (4)
  * Re-write chat menu
  * Added a user option for online friends count. This is hidden by default
  * Changed emoji button in chatbox to use a PNG icon
  * Removed use of the MDL2 assets font as it was only in use by one element
* **Fixes** (2)
  * 'Welcome to your server' message is once again hidden by default
  * Chat scrolling up when pressing Up Arrow to edit a message

#### 3.9.2
* **Fixes** (1)
  * Buttons offset from toolbar

#### 3.9.1
* **Enhancements** (3)
  * Restyle chat dividers
  * cosy mode chat is now shown in bubbles
  * Re-write toolbars
* **Fixes** (5)
  * Made settings window menu style only apply when dark theme is selected
  * Added a 5px dead zone on the edge of some elements to prevent hover state remaining stuck on when the cursor leaves the Discord window. There are some niche cases where the bug can still occur (eg. Discord snapped against another window).
  * Settings button
  * Members list typing status position
  * Adjust position of badge in Friends/Games select tabs
* **Notes** (1)
  * Fallback fonts (Selawik and winjs-symbols) have been removed. If you do not have SegoeUI or SegoeMDL2 Assets you may experience problems

#### 3.9.0
* **Enhancements** (3)
  * New home tab
  * Remove online user count from the guilds list
  * Changed icon of former friends 'guild'
* **Fixes** (1)
  * Guild selected text colour
* **Clean-up** (2)
  * `/src/friends` has been renamed `/src/home` with Friends and Games tabs organised into their respective subdirectories
  * Delete `/src/login` as it is no longer required

#### 3.8.13
* **Fixes** (1)
  * Guild icons were oversized due to a discord update
* **Known Issues** (1)
  * Group DM invite popout - this will be fixed at a later date

#### 3.8.12
* **Fixes** (1)
  * Chatbox textarea was pushed right when the user had Spotify integration enabled

#### 3.8.11
* **Fixes** (2)
  * Remove attachment button divider
  * Disabled chatbox placeholder alignment

#### 3.8.10
* **Fixes** (1)
  * Chatbox autocomplete background

#### 3.8.9
* **Enhancements** (3)
  * Added hover states to microphone and speaker muting buttons
  * Make chatbox scrollbar more visible
  * Some alignment and sizing changes to the account box and version info area
* **Fixes** (3)
  * Chatbox upload and emoji buttons
  * Upload modal comment box emoji button
  * Editing message emoji button

#### 3.8.8
* **Fixes** (3)
  * Remove wumpus<sup>(ugh)</sup> from user popout. This would normally only appear on newly registered users
  * Override input and textarea placeholder fonts
  * Members list scrollbar visibility

#### 3.8.7
* **Enhancements** (1)
  * Corrected HEX default accent colour
* **Fixes** (6)
  * Chat box placeholder font
  * Chat editing message
  * Upload modal comment box margins
  * Recent/Pinned messages popouts were out of position
  * User popout DM textbox
  * Chat options menu right margin

#### 3.8.6
* **Fixes** (5)
  * Revert change made to system message icon
  * Server settings bans search box
  * Server settings remove emoji, revoke invite buttons
  * Server settings emoji alias text moved position when hovered
  * RTC channel name line-height

#### 3.8.5
* **Enhancements** (1)
  * Embedded Audio/Video players
* **Fixes** (2)
  * Editing message autocomplete
  * NSFW channel warning Continue button

#### 3.8.4
* **Fixes** (1)
  * Reduce chat indenting

#### 3.8.3
* **Enhancements** (1)
  * Re-write chat CSS
* **Fixes** (6)
  * Upload modal comment box
  * Chat timestamps will now position correctly if the time is not in H:i format
  * Upload modal mention list
  * Server settings user list search bar
  * Update Recent Mentions, Pinned messages and emoji picker classes 
  * BetterDiscord: Fix settings padding

#### 3.8.2
* **Enhancements** (3)
  * Change background of settings sidebar
  * Remove social media links from settings sidebar
  * New chatbox design
* **Fixes** (1)
  * Codeblock header was out of position

#### 3.8.1
* **Enhancements** (3)
  * Some improvements and fixes to friends conversations list
  * Change appearance of chat dividers
  * Future-proofing of popouts
* **Fixes** (1)
  * Update classes of many elements where their class names had been re-rolled. See [#26](https://github.com/TakosThings/Metro-for-Discord/issues/26)

#### 3.8.0
* **Enhancements** (4)
  * Instant invite modal
  * Re-write Friends messages list
  * Remove search bar from friends DM messages list
  * Remove guilds separator
* **Fixes** (3)
  * Friends server icon will highlight in white when Friends is open to match behaviour to that of normal servers
  * Friends toolbar utility icons
  * User popout opening in wrong position if summoned from cosy mode avatar

#### 3.7.7
* **Fixes** (1)
  * Update the following popouts;
    * Search
    * Recent mentions
    * Pinned messages
    * Emoji picker (see notes for this release)
    * User popout
    * Add participant to group DM
    * Add role (from user popout)
    * Server dropdown
    * Status changer
* **Notes** (1)
  * Emoji picker may sometimes open in the top right of the client when adding a reaction via the chat options button.

#### 3.7.6
* **Enhancements** (1)
  * Rewrite `/popout/_search.scss` for style update
* **Fixes** (1)
  * Bot tags

#### 3.7.5
* **Fixes** (2)
  * Recent Mentions/Pinned messages popout
  * Fix members list margins

#### 3.7.4
* **Fixes** (3)
  * Unblock button in user DM chatbox area
  * Add role button in user popout
  * Update class names for members list

#### 3.7.3
* **Enhancements** (1)
  * Rewrite `/primary/members/_members.scss` for style update
* **Fixes** (6)
  * Branded link button
  * SCSS variable used # instead of $ in `/modal/_upload.scss`
  * Listen along invite modal chatbox
  * Listen along invite modal sub headers
  * Listen along invite modal Spotify invite
  * User popout quick message focus state

#### 3.7.2
* **Fixes** (2)
  * Speculative fix: Emoiji picker opening in centre of screen when opened from 'Add Reaction' button
  * User popout quick message

#### 3.7.1
* **Fixes** (1)
  * Update context menu class

#### 3.7.0
* **Enhancements** (1)
  * Attach menu
* **Fixes** (3)
  * Disabled Spotify listen along button in user popout
  * Disabled Spotify listen along button in user modal
  * Spotify chat embed buttons

#### 3.6.8
* **Fixes** (4)
  * Add streaming class to user popout header
  * Spotify listen along button in user popout
  * Spotify listen along button in user modal
  * Update send friend request button classes in user modal

#### 3.6.7
* This release corrects a change made to chatbox margins, but was not properly bug checked before release.

#### 3.6.6
* **Fixes** (2)
  * User popout opening in default position when user had cosy mode enabled and 'Chat font scaling' or 'Zoom level' were changed from values of 90% and 100% respectively
  * Chat box margins when uploading files is disabled in that channel

#### 3.6.5
* **Fixes** (2)
  * Speculate fix for user popout moving under titlebar
  * Fix user popout moving under titlebar if PermissionsViewer plugin was activated

#### 3.6.4
* **Fixes** (1)
  * Partially fix a bug which caused the emoji picker to display in top-right corner of Discord if opened from existing reactions.
* **Known Issues** (1)
  * Emoji picker displays in the centre of application if opened from 'Add reaction' button (next to chat options, not existing reactions). Progress is being tracked in [#16](https://github.com/TakosThings/Metro-for-Discord/issues/16).

#### 3.6.3
* **Enhancements** (1)
  * Left align text in chat options menu
* **Fixes** (1)
  * User popout not opening in correct position if user had cosy mode enabled

#### 3.6.2
* **Enhancements** (6)
  * Copy box
  * Audit log
  * Quick select popout
  * Move lightbox download link to right
  * Redesigned user popout
  * Change hover state of members list
* **Fixes** (9)
  * Dropdown box sizing
  * Some buttons missed in last pass
  * Server settings members list role tags
  * No content warning (eg. Server settings > Integrations > "No integrations" message)
  * Some generic modal layouts
  * Settings save alert
  * More fixes for generic modals
  * Modal close button position
  * Members list role header showed select text mouse cursor when hovered
* **Notes** (1)
  * User popout has been re-written. If you notice any major problems, please [open a new issue](https://github.com/TakosThings/Metro-for-Discord/issues/new).

#### 3.6.1
* **Enhancements** (2)
  * Changed background of voice connected badge
  * Added uservar to easily allow changing the background of the voice connected badge
* **Fixes** (3)
  * Added missing uservar to userstyle
  * Buttons
  * Invite modal button alignment

#### 3.6.0
* **Enhancements** (8)
  * Search in toolbar will now hide itself when not in use
  * Spotify embed
  * Invite modal
  * Phone verification modal
  * Remove sticky header from emoji picker
  * Adjust vertical position of emoji picker
  * Red outlined button
  * Connections
* **Fixes** (12)
  * Mention hover state
  * Remove avatar masking from user popout
  * Long usernames in user popout overflowing if a nickname was set
  * Remove top right border radius from notices
  * Notice dismiss button
  * Adjust height of theme warning notices to match Discord's
  * Truncate long file names of attachments
  * My account header in settings
  * Double border on connection toggle switch
  * Nitro settings sidebar hover background colour
  * Disabled dropdown hover state
  * Keybinds warning message
* **Notes** (1)
  * User/Server/Channel settings CSS has been re-written. If you notice any major problems, please [create a new issue](https://github.com/TakosThings/Metro-for-Discord/issues/new) on the repo.

#### 3.5.0
* **Enhancements** (5)
  * No text channels error message
  * Role titles in members list are now auto-capitalised
  * Attachments (Some unfinished code was pushed in error in the previous release, this update remedies that)
  * Use default cursor when hovering over menu options in User Settings
  * User popout Spotify integration
* **Update** (2)
  * Quickswitcher
  * Keybinds
* **Fixes** (15)
  * Some elements on login screen
  * Loading screen
  * Direct Messages header highlighting when hovered
  * GIF tag on embedded images
  * Some letters being cut off in profile modal
  * Profile modal note textarea
  * Profile modal scrollbar
  * Friends list scrollbar will only be shown when it's required
  * Line height of assigned roles in user popout
  * Phantom scrollbar appearing on codeblocks when no language was defined
  * Nitro sidebar option in User Settings now obeys convention
  * Grey background on Spotify user popout
  * Emoji picker dimmer sizing
  * Emoji picker diversity selector icon jumping when menu was open
  * User popout instant message input sizing

#### 3.4.3
* **Update** (9)
  * Emoji picker
  * Lightbox
  * Server dropdown menu
  * Status change menu
  * RTC popout
  * Server region select
  * Dropdown inputs
  * Nitro settings sidebar option text colour
  * Upload modal
* **Fixes** (12)
  * Context menu checkmark position
  * Some user popout selectors for inputs
  * Chatbox autocomplete applying style to another unrelated element (autocomplete popout)
  * Search popout applying style to autocomplete popout (animation and positioning)
  * Remove pro tip from pinned messages
  * Unread guilds notification no disappearing even if guilds were scrolled to the bottom of the list
  * Loading animations
  * Typing animation in members list was playing the loading spinner GIF
  * Update search datepicker classes
  * Game name input boxes should now be uniform with other inputs
  * Some checkboxes in Privacy and Safety settings had rounded edges
  * Start of channel history message
* **Clean-up** (1)
  * Remove some unused code from `/friends/_add_friend.scss` (Not worth updating)
* **Known issues** (3)
  * Instant invite modal has been reverted to default style. It's currently marked as deprecated, therefore will not be fixed until it's revamped.
  * Add game popout is having animation and positioning CSS applied to it from pinned/recent messages.
  * Attachments embedded in chat (eg. zip, text files etc.) have reverted to the default icons. A fix is being researched.

#### 3.4.2
* **Enhancements** (2)
  * Made scrollbar in autocomplete easier to use when searching Giphy
  * Change appearance of "GIF" text in embedded gifs
* **Update** (4)
  * Context menu
  * "X is typing..." message
  * Server welcome message
  * Embeds

#### 3.4.1
* **Enhancements** (1)
  * User popout roles
* **Fixes** (5)
  * Settings sidebar regression
  * Rounded edges on settings checkboxes
  * Loading animations
  * New unread notification bar in guilds pane
  * New unread notification bar in channels pane
* **Clean-up** (1)
  * Remove roles CSS from `/popout/_user.scss` (Old code)

#### 3.4.0
* **Enhancements** (2)
  * Make corners of flag icons square
  * Change the titlebar close button hover background colour
* **Update** (3)
  * New user profile
  * New user popout
  * New invites
* **Fixes** (5)
  * Channel name in toolbar clipping the bottom of some letters
  * Remove border radius on left side of channels pane
  * Remove top/bottom margins from chatbox
  * Account box mic/speaker control icons
  * RTC box

#### 3.3.1
* **Fixes** (4)
  * Channel notification badge
  * Channel name in toolbar clipping the bottom of some letters
  * Truncate long server names in guilds list
  * Truncate long notification badge in guilds list

#### 3.3.0
This update contains primarily fixes for 'that titlebar update that broke everything else'.
* **Enhancements** (2)
  * A variable to change the colour of links in chat is now available in the user options section.
  * Change background colour of guilds list
* **Update** (5)
  * New titlebar
  * Settings icon
  * Channels list
  * Toolbar
  * Chatbox
* **Clean-up** (1)
  * Remove `/icons/_titlebar.scss` (Icons not required anymore)
* **Fixes** (1)
  * Video calling icon was default
  * Tooltips text colour

#### 3.2.3
This Update reverts changes made in 3.2.2
* **Fixes** (1)
  * Tooltips and some popouts such as emoji picker, recent mentions and pinned messages displaying much lower than they should

#### 3.2.2
* **Fixes** (1)
  * Tooltip vertical misalignment

#### 3.2.1
* **Enhancements** (4)
  * Decrease padding between channel categories
  * Some changes to NSFW channel warning
  * Chat attachments (and icons)
  * Upload file modal icons
* **Fixes** (3)
  * Style not being correctly applied to first channel category in some cases
  * Upload file modal icon position/sizing
  * Upload file modal header
* **Other** (1)
  * Remove novelty feature from user profile modal

#### 3.2.0
* **Enhancements** (1)
  * Channel categories
* **Clean-up** (2)
  * Delete `/notices/_font_scaling.scss` (was supposed to be removed in 3.1.0)
  * Delete `/modal/_deprecated_rtc_debug.scss` (was superseded)
* **Fixes** (3)
  * Chatbox attach button sizing
  * Channels new mentions bar
  * Guilds new mentions bar text case

#### 3.1.2
* **Enhancements** (2)
  * Profile modal rich now playing
  * Chatbox unblock user
* **Fixes** (5)
  * Text/Voice channel section headers
  * Remove border on profile popout status circle
  * Profile popout now playing text
  * Toolbar #/@ symbol colour
  * Context menu checkbox background

#### 3.1.1
* **Fixes** (2)
  * Left chat padding when font scaling is increased
  * Chatbox font scaling

#### 3.1.0b
* **Fixes** (1)
  * Remove font scaling warning

#### 3.1.0
* **Enhancement** (3)
  * Chat font will now scale correctly above or below the default value [Closes #12](https://github.com/TakosThings/Metro-for-Discord/issues/12)
  * Userstyle users will now be able to configure the theme on the userstyles.org page
  * Theme x Blocked Message bars
* **Adjustments** (1)
  * Change padding and positioning of header in RTC popout
* **Fixes** (2)
  * Top margin appearing on connecting screen when no titlebar is present (Userstyle)
  * Hide blocked messages was declared twice

#### 3.0.1
* **Fixes** (7)
  * Tooltip background colours
  * Chatbox left margin if file uploads are disabled on that channel
  * Custom emoji sizing in emoji picker
  * Autocomplete popout scrolling bug
  * Autocomplete popout scrollbar
  * Autocomplete popout list default role text colour
  * Selected role background-colour in server settings
