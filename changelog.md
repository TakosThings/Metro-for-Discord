# Changelog
Newest changes are at the top

#### 2.22.5
* Changed channels selected/unread colours so they match the guilds
  * Unread channels will be highlighted with your `--accent` colour
  * The selected channel will be highlighted white

#### 2.22.4
* **Fixes**
  * Fix badges

#### 2.22.3a
* Re-add version info under account

#### 2.22.3
* Port new channels style from v3 branch

#### 2.22.2
* **Fixes**
  * Fix issue #3

#### 2.22.1
* **Fixes**
  * Fix issue #2
  * Channel font sizes

#### 2.22.0
* The Selawik font will be imported and used automatically if Segoe UI is not present
* Remove chevron icon and use CSS to make one instead
* Change appearance of settings menu separators
* Move BetterDiscord version number next to the section header
* Use a variable to change version info and move the pseudo to where it should belong in the code
* Logout option in settings menu will now use the colour defined in the `--alert` variable
* Added `@font-face` to import the Selawik font if Segoe isn't available
* Some more code organising
* **Fixes**
  * Cludge for the the new channels bar

#### 2.21.0
* **Discord has started to obfuscate some elements. The following have been updated, but could potentially break again without warning :(**
  * Buttons
  * NSFW channel warning
* Cleaning
* Add status text to members list while it is loading. An error message will be shown after 60 seconds.
* Many fixes and adjustments to upload file modals
* New icons for uploaded files
* Add background to emoji picker header to hide section headers appearing behind search box
* Remove background fade from under Quickswitcher input
* Update Quickswitcher scrollbar
* Update private calling
* Remove old user settings animations
* Move all icons into same area of CSS
* Optimise and substitute some icon files
* **Fixes**
  * BetterDiscord Open Theme/Plugins folder button
  * Server settings member name colour
  * White gap at the botton of some generic modals
  * Upload modal chat box emoji button positioning
  * System message chat icon position
  * System message timestamp colour
  * Audit logs username text colour
  * Search not opening when search button clicked

#### 2.20.1
* **Fixes**
  * Friends pending tab badge background when tab selected
  * Chat box emoji button position
  * Quick select search box sizing

#### 2.20.0
* Show code language in code blocks (May be removed in future)
* Adjust some colours of codeblocks
* Monokai syntax highlighting for codeblocks
* New badges style
* Added variables to change the status colours
* Some style changes to '/' commands box
* Restyle status changer
* Rewrite Emoji picker (also fixes various bugs the picker had previously)
* Remove duplicated icon (was used in search date picker)
* Remove shit maymay from emoji selector
* Remove EvenBetterRepo support
* Remove unused log off icon
* Remove unused channel settings icon
* **Fixes**
  * Search date picker stealth update
  * Search history query text colour
  * Instant Invite modal header would overflow if server name was too long
  * Help text in Instant Invite modal was wrong colour
  * Nitro info width
  * Keybinds warning was still default style
  * Game name input boxes had incorrect hover and focus states
  * Textbox headers in user account info
  * 'AKA' tag style
  * Search bar showing a scrollbar if query was too long
  * Search bar text was bold
  * Some neglected CSS relating to scrollbars
  * Context menu sub menu arrow
  * Private channels search icon positioning
  * "(edited)" chat text colour
  * Direct messages Now playing text

#### 2.19.0
* Icons for new settings menu items
* **Fixes**
  * Notification settings modal wasn't styled
  * Instant invite copy box wasn't styled
  * Input boxes in user popout had no hover state
  * Some icons would display inside the roles list in server settings
  * Service logos in Connections weren't styled
  * Password confirmation and 2FA input boxes stretched out-of-bounds
  * Horizontal tab bars in Profile modal and Recent Mentions popout weren't styled
  * Add friends to DM search box wasn't styled
  * Collapse voice channel icon needlessly loaded another icon, identical to collapse text channel

#### 2.18.0
* Rewrite New settings
* Beginning of channel history header
* Increase font-size of chatbox to 15px
* Adjust sizing of chatbox upload and emoji buttons
* Remove Wumpus' from user profile modal
* Titlebar is now visible while connecting screen is shown
* Move Twitter and StatusPage links on connecting screen to lower right
* **BetterDiscord**
  * Remove Public servers style
  * Remove Monokai CodeMirror theme
  * Add warning to disable BD Blue mode
* **Updated icons**
  * Instant invite
  * Channel collapse
  * Modal close button
* **Fixes**
  * Recent mentions tabs had no hover state
  * Toolbar buttons wrong hover background-color
  * Search bar width should match width of search poput
  * Members list roles header font-weight
  * Help modal placeholder text colour
  * Chatbox placeholder text colour
  * Account mic/speaker controls had wrong hover background-colour
  * 'Change to lightmode' warning appearing in context menu
  * Jagged 'Connecting' text in connecting screen
  * Markdown modal body padding

#### 2.17.0
* Canary NSFW channel warning
* Canary Server Settings
* **Fixes**
  * Update ready button not using theme icon
  * Pinned message chat notification not using theme icon

#### 2.16.5
* **Fixes**
  * 'Open Original' button in image lightbox

#### 2.16.4
* Update `#voice-connection` to `#rtc-connection`
* **Fixes**
  * line-height of clipboard box

#### 2.16.3
* **Fixes**
  * Updated toolbar icons not displaying after stealth Discord update

#### 2.16.1
* **Fixes**
  * Toolbar button icons dimming when hovered

#### 2.16.0
* Quick switcher
* Quick switcher channel notice
* Make search bar appear as a button
* Make search popout display like recent mentions and pinned messages
* **Fixes**
  * Channel members list scrolling bug
  * Font colour for safety level tips

#### 2.15.0
* New Settings
* **Fixes**
  * Timestamp text colour
  * Slider handles glitching when panning

#### 2.14.0
* Load more messages chat button
* Change user popout style
* Change font size of member group
* Change loading icon to Windows 8/10 circles
* Theme connecting screen (also remove maymays)
* Adjust margins of chat box
* Various minor improvements to some elements in server/channel settings modals
* Plugin support for Clock
* Plugin support for CopyCode
* Plugin support for OwnerTags (CSS provided by @supersmilers)
* Plugin support for Renamer
* **Fixes**
  * Speculative fix for an issue causing the plus symbol in add guild button to move out of bounds
  * Correct default user colour in members list
  * Default user tag style in user popout
  * Bot tag text alignment
  * Bot tag colours in user popout
  * Nickname textbox width
  * Incorrect scrollbar track background colour in profile popout
  * Need help modal textbox focus and hover border color
  * Voice info/disconnect icons dimming when hovered
  * Search members textbox placeholder
  * Currently selected guild not showing border when hovered

#### 2.13.4
* **Fixes**
  * No left border on emoji popout if user didn't have BD emote menus enabled
  * Sizing fix for offline server tile

#### 2.13.3
* **Fixes**
  * Emote picker not highlighting selected tab when using BetterDiscord's Dark Mode

#### 2.13.2
* **Fixes**
  * BetterDiscord's Dark Mode fiddling with the emote/emoji menu CSS

#### 2.13.1
* **Fixes**
  * Loading gif showing up in the members list when people were typing

#### 2.13.0
* Rewrite Guilds style
* Change channel section header style
* Change unread channel indicator style
* Change some styling for dropdown boxes
* Change Now Playing settings style
* Some styling for forms in BD plugin settings
* Hide the "TEMPDISABLED" checkbox under Custom CSS editor
* Remove commented out backdrop code
* Authorised Applications
* Make mute icons in notification settings brighter
* Loading animation
* **Fixes**
  * Updated Nitro style
  * Alt theme checkboxes
  * Font used in dropdowns
  * Long broken locale dropdown
  * Streamer mode settings tab had white background
  * BD theme/plugin enable checkbox font colour
  * BD theme/plugin enable checkbox positioning
  * BD plugin settings modal border colour
  * Disabled button style

#### 2.12.1
* **Fixes**
  * Flickering usernames when hovering on messages or avatars in cozy mode
  * Use accent colour for border of voice connection info popout
  * Bad text colours of bot embeds
  * Incorrect top margins of settings modal, overlapping the windows titlebar
  * Tipsy tooltips positioning
  * Double border on markdown modals
  * Make profile popout avatar background transparent

#### 2.12.0
* Clickable links to the Github repo have been removed from META
* Muted microphone and speaker icons in voice channels now match the theme
* Added an animation for Recent and Pinned messages
* Added horizontal scrollbar to `/giphy` search
* Adjust height of roles section in user popout
* Clyde bot local message
* **Fixes**
  * Left/Right padding on textbox guard if window was too narrow
  * Change nickname modal input box was too wide
  * Incorrect border colour on search popout
  * Incorrect border colour on various modals
  * CodeMirror CSS highlighting `!important`s in blue making it impossible to read
  * Code background in markdown modal
  * Positioning of unread messages (up/down) indicators
  * Bad text colour for invite buttons
  * Checkboxes in create channel modal stacking height
  * Scrollbar track colour

#### 2.11.0
* Re-worked emote/emoji picker
* Friends button will now highlight when selected
* Added 8px gap to first and last context menu items
* "Cannot message blocked users" textbox in user popout
* Unblock button in DM message area
* Remove shit meme from help modal
* "Streamer mode enabled" button
* **Fixes**
  * Message context and Add Reaction menu buttons on chat messages were exceptionally hard to click on (caused by backface-visibility)
  * Some incorrect font-weights
  * Channels not displaying correctly if the list was longer than the window
  * White vertical line appearing in settings modal menu
  * "Playing" and game text in members list were slightly offset

#### 2.10.0
* Search
* Added var for monospace font
* Keyboard shortcuts modal
* Change glyph for .gif files
* Upload file progress bar
* Upload file icon
* Upload file error modal
* Drag & drop file modal
* Re-enabled modal/lightbox backdrop
* Scrollbars now have hover and active states
* **Fixes**
  * line-height on BetterDiscord plugin/theme descriptions
  * Remove placeholder image if there are no previous DMs

#### 2.9.0
* Add program title in titlebar
* Join server countdown timer
* Set backface-visibility to hidden
* Nitro settings
* **Fixes**
  * Mention text
  * "Playing" text in user popout was wrong colour
  * "View profile" circle on user popout didn't fill the entire avatar
  * Edit message box had no right margin in cozy mode
  * Guild error tile was too large
  * Padding on Notification Settings table header

#### 2.8.2
* Minify META repo link
* **Fixes**
  * Discoloured message timestamps when hovered

#### 2.8.1
* **Fixes**
  * Vertical alignment on roles delete button
  * Vertical alignment on settings/New Server button

#### 2.8.0
* Monokai theme for CSS editor
* Settings and create server buttons will now change background colour when hovered
* Some unstyled elements on add friends page
* Various style fixes on create/join modal
* Pass over upload modal to fix margins and preview positioning
* Pass over all buttons to make sure they all behave, look and represent the same
* Role colour picker
* Automatically assigned role warning
* Overlay warning
* Remove image from Server Security settings
* Remove image from Server Emoji settings
* Remove protips
* Remove stupid .gif from ban user modal
* Themed scrollbar for roles list in user popout
* Themed scrollbar for edit message box
* Public servers list button
* Public servers list
* **Fixes**
  * Upload modal emoji button now won't overflow when hovered
  * Create group DM button was hidden
  * Guild unread messages indicator bottom positioning
  * Some help text in server settings which changed size for no particular reason
  * Connections help text was incorrectly coloured
  * Radio buttons were oversized
  * BetterDiscord plugin settings text was black, making text unreadable
  * Background on edit message field will now appear when using cozy mode
  * Muted channel toolbar icon wasn't being replaced
  * Giant gaps between messages in Recent Mentions popout
  * Discoloured text on Recent Mentions filter
  * Add Friend button badge discoloured text
  * Friends channel badge positioning
  * Friends mutual server icon background colour (fixes jagged border if server uses an icon instead of text)
  * Ban list
  * Incorrect colour for "Trust this domain"

#### 2.7.0
* Added visual feedback to guilds hover/active state
* Invited to server modal
* Vanity text in my profile modal

#### 2.6.0
* Update: New profile modal
* Update: Embeds

#### 2.5.1
* **Fixes**
  * Accept/Ignore friend request buttons changing position when row was hovered
  * Pending button badge positioning

#### 2.5.0
* Make emote/emoji button in chat box a normal icon
* Favourite emote context menu
* Add scrollbar to chatbox to make formatting long messages (particularly codeblocks) easier
* Pass over BetterDiscord theme/plugin settings
* Plugin support: Even Better Repo
* Plugin support: Creation Date
* **Fixes**
  * Settings button had a background when state was active
  * Text boxes in settings modals were slightly too tall
  * Change password text was wrong colour
  * Remove avatar link font-weight
  * Remove jagged border on avatar in settings modal
  * Remove a white border in Connections settings
  * Low-readability embeds text
  * Low-readability 2FA backup codes
  * Display notes textarea in user popout correctly
  * Notes textarea in user popout should now expand to display input
  * Guild initialism will add ellipsis to the end if it overflows the box
  * Mentioned chat highlight had rounded borders
  * Gap on right side of chat
  * User status text getting cut off in the friends table
  * User roles text getting cut off in user popout
  * Unreadable voice diagnostics

#### 2.4.0
* Reactions (even though they're fucking stupid)

#### 2.3.0
* No longer beta
* Added custom icons to emoji category selector
* **Fixes**
  * position of dimmer when diversity selector is open

#### 2.2.1
* **Fixes**
  * Checkboxes and buttons weren't using the user defined accent colour

#### 2.2.0
* Add background colour to edit message field, and scrollbar to make editing long messages easier
* **Fixes**
  * 1px gap on emote/emoji tabs

#### 2.1.1
* **Fixes**
  * BetterDiscord plugin settings popup was white, making text unreadable

#### 2.1.0
* Release v2