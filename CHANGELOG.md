# Changelog
Newest Changes are at the top

#### 3.2.1
* **Enhancements**
  * Decrease padding between channel categories
  * Some changes to NSFW channel warning
  * Chat attachments (and icons)
  * Upload file modal icons
* **Fixes**
  * Style not being correctly applied to first channel category in some cases
  * Upload file modal icon position/sizing
  * Upload file modal header
* **Other**
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
* **Fixes**
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
