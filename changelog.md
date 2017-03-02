# Changelog
Newest changes are at the top

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
* Loading animaiton
* Fixes
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
* Fixes
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
* Fixes
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
* Fixes
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
* Fixes
  * line-height on BetterDiscord plugin/theme decriptions
  * Remove placeholder image if there are no previous DMs

#### 2.9.0
* Add program title in titlebar
* Join server countdown timer
* Set backface-visibility to hidden
* Nitro settings
* Fixes
  * Mention text
  * "Playing" text in user popout was wrong colour
  * "View profile" circle on user popout didn't fill the entire avatar
  * Edit message box had no right margin in cozy mode
  * Guild error tile was too large
  * Padding on Notification Settings table header

#### 2.8.2
* Minify META repo link
* Fixes
  * Miscoloured message timestamps when hovered

#### 2.8.1
* Fixes
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
* Fixes
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
  * Miscoloured text on Recent Mentions filter
  * Add Friend button badge miscoloured text
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
* Fixes
  * Accept/Ignore friend request buttons changing position when row was hovered
  * Pending button badge positioning

#### 2.5.0
* Make emote/emoji button in chat box a normal icon
* Favourite emote context menu
* Add scrollbar to chatbox to make formatting long messages (particularly codeblocks) easier
* Pass over BetterDiscord theme/plugin settings
* Plugin support: Even Better Repo
* Plugin support: Creation Date
* Fixes
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
* Fixes
  * position of dimmer when diversity selector is open

#### 2.2.1
* Fixes
  * Checkboxes and buttons weren't using the user defined accent colour

#### 2.2.0
* Add background colour to edit message field, and scrollbar to make editing long messages easier
* Fixes
  * 1px gap on emote/emoji tabs

#### 2.1.1
* Fixes
  * BetterDiscord plugin settings popup was white, making text unreadable

#### 2.1.0
* Release v2