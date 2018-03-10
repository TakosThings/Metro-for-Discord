# Changelog
Newest Changes are at the top

#### 3.6.6
* **Fixes** (2)
  * User popout opening in default position when user had cozy mode enabled and 'Chat font scaling' or 'Zoom level' were changed from values of 90% and 100% respectively
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
  * User popout not opening in correct position if user had Cozy mode enabled

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
  * Remove protip from pinned messages
  * Unread guilds notification no disappearing even if guilds were scrolled to the bottom of the list
  * Loading animations
  * Typing animation in members list was playing the loading spinner GIF
  * Update search datepicker classes
  * Game name input boxes should now be uniform with other inputs
  * Some checkboxes in Privacy and Safety settings had rounded edges
  * Start of channel history message
* **Cleanup** (1)
  * Remove some unused code from `/friends/_add_friend.scss` (Not worth updating )
* **Known issues** (3)
  * Instant invite modal has been reverted back to default style. It's currently marked as deprecated, therefore will not be fixed until it's revamped.
  * Add game popout is having animation and positioning CSS applied to it from pinned/recent messages.
  * Attachments embedded in chat (eg. zip, text files etc.) have reverted back to the default icons. A fix is being researched.

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
* **Cleanup** (1)
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
* **Cleanup** (1)
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
  * Tooltip vertical mis-alignment

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
* **Cleanup** (2)
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
