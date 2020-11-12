# Contributing

## Reporting Issues
* Disable BetterDiscord plugins and addon themes before opening an issue. 
* Use the provided *Bug report* template when opening a new Issue.
  * You may delete the placeholder help text under each header if you wish.
* Please don't 'bulk report' unrelated issues in the same Issue.
* Please don't report a new issue in the thread of an existing issue if it is unrelated.
* Please don't open an issue if your problem relates directly to BetterDiscord or if a BetterDiscord plugin or addon theme is causing a conflict with this theme. 
* Search through existing issues before adding a new *Feature request*. These issues are tagged with the `Feedback` label.

## Pull Requests
* Open an issue using the *Change proposal* template to discuss your changes
* Clone/rebase this repo
* Make sure your editor is obeying `.editorconfig`. <sup>[What's this?](https://editorconfig.org/)</sup>
  * To test: Try removing the blank new line at the end a file, then save. Everything is working properly if a blank new line is added back after saving.
* Make any changes in a new branch (not `master`)
* Submit a PR, be sure to reference the initial discussion issue

### Developing
#### Ingredients
* An editor (like [Visual Studio Code](https://code.visualstudio.com/))
* [Git](https://git-scm.com/)
* [Node JS](https://nodejs.org/en/)
* [Editorconfig Plugin](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig/) (if you're using VS Code)
#### Method
* Run `npm i`
* Use `npm run watch` to automatically compile the theme as you work

### Things to know
* All development and testing is done using BeautifulDiscord, which can auto-reload the theme as you work

### BetterDiscord
Additions for BetterDiscord plugins are welcome, however I likely won't update them over time. Please submit a PR for plugin additions or updates.
* The plugin **must** be approved and listed in the BetterDiscord plugin repos.
  * Support will be removed if the developer leaves the BetterDiscord server or is removed from the developer role.
* File location and naming convention
  * Plugin support files shall be located within `/src/components/betterdiscord/plugins/`
  * Each plugin shall have it's own SCSS file using the following naming scheme `_GithubUsername.PluginName.scss`. Capitalisation should be the same as the developer's GitHub username, and plugin name.
  * Import the plugin in `/src/components/betterdiscord/_plugin_support.scss`
