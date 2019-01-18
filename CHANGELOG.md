# Changelog
Newest Changes are at the top

#### 3.10.1
* **Enhancements** (1)
  * Increased spacing between buttons and the searchbar when search is active
* **Fixes** (4)
  * Remove border on status indicator in account area
  * DMs avatar size in guilds list
  * Search bar clear icon not visible when search bar is active
  * 'Search for' in search popout had incorrect background colour

#### 3.10.0
* **Housekeeping** (5)
  * Userstyle will no longer be updated. Related `/dist/` and  `/src` files have been deleted.
  * *Metro for Discord* Userstyles.org entry has been archived.
  * A CONTRIBUTING.md file will be introduced shortly after this release. This version will cover the scope of the project. Details on development of the theme will come later.
  * Delete `/src/components/modal/_deprecated_help.scss`, as Help modal has been removed
  * Delete `/src/components/core/_font.scss`, as it was marked for deletion in  v`3.9.1`
* **Enhancements** (4)
  * Channel notices have been removed
  * Superfluous *Gift Nitro* and *GIF* buttons have been removed from the chatbox. These features can still be accessed via the User Settings and `/tenor` or `/giphy` commands respectively
  * 'Press CTRL+K to Search' help text has now been removed
  * Rewrite search results pane
* **Fixes** (10)
  * Update @ and # mentions in recent mentions popout
  * Fix message preview in the Delete Message modal
  * Chatbox autocomplete
  * ~~Un-fix emoji picker search bar (what even, Discord?)~~ Nevermind, Re-fix the un-fix of the fix
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
  * Incorrect css being applied to badge in friends list
  * Call toolbar not themed

#### 3.9.13 (1)
* **Enhancements**
  * Revert a previous commit that changed the functionality of the search bar. The required class for this feature was returned
* **Fixes** (1)
  * Update settings classes

#### 3.9.12
* **Changes** (1)
  * Search bar will no longer colapse when not in use due to a change in functionality
* **Fixes** (2)
  * Seach popout
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
  * Re-wite keyboard shortcuts modal
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
  * Changed emoji button in chatbox to use a png icon
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
  * Cozy mode chat is now shown in bubbles
  * Re-write toolbars
* **Fixes** (5)
  * Made settings window menu style only apply when dark theme is selected
  * Added a 5px deadzone on the edge of some elements to prevent hover state remaining stuck on when the cursor leaves the Discord window. There are some neiche cases where the bug can still occur (eg. Discord snapped against another window).
  * Settings button
  * Members list typing status position
  * Adjust position of badge in Friends/Games select tabs
* **Notes** (1)
  * Fallback fonts (Selawk and winjs-symbols) have been removed. If you do not have SegoeUI or SegoeMDL2 Assets you may experience problems

#### 3.9.0
* **Enhancements** (3)
  * New home tab
  * Remove online user count from the guilds list
  * Changed icon of former friends 'guild'
* **Fixes** (1)
  * Guild selected text colour
* **Clean up** (2)
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
  * Memberslist scrollbar visibility

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
  * User popout opening in wrong position if summoned from cozy mode avatar

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
  * Listen along invite modal subheaders
  * Listen along invite modal spotify invite
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
