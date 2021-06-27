# Contributing

## Reporting Issues
* Disable BetterDiscord plugins and addon themes before opening an issue. 
* Use the provided *Bug report* template when opening a new Issue.
  * You may delete the placeholder help text under each header.
* Please don't 'bulk report' unrelated issues in the same Issue.
* Please don't report a new issue in the thread of an existing issue if it is unrelated.
* Search through existing issues before adding a new *Feature request*. These issues are tagged with the `Feedback` label.

## Pull Requests
* Open an issue using the *Change proposal* template to discuss your changes before starting.
* Clone/rebase this repo.
* Make sure your editor is obeying `.editorconfig`. <sup>[What's this?](https://editorconfig.org/)</sup>
  * To test: Try removing the blank new line at the end a file, then save. If a blank new line is added back after saving that means everything is working properly.
* Make any changes in a new branch (not `master`).
* Submit a PR, be sure to reference the initial discussion issue.

### Developing
#### Ingredients
* An editor (like [Visual Studio Code](https://code.visualstudio.com/))
* [Git](https://git-scm.com/)
* [Node JS](https://nodejs.org/en/)
* [Editorconfig Plugin](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) (if you're using VS Code)
#### Method
* Run `npm i sass -g`
* Use `npm run watch` to automatically compile the theme as you work

### BetterDiscord Plugins
Additions for BetterDiscord plugins are welcome, however I likely won't update them over time. Please submit a PR for plugin additions or updates.
* The plugin **must** be approved and published on [betterdiscord.app](betterdiscord.app).
  * Support will be removed if the plugin is removed from the website.
* File location and naming convention
  * Plugin support files are located within `/src/components/betterdiscord/plugins/`
  * Each plugin has a SCSS file using the following naming scheme: `_GithubUsername.PluginName.scss`.
    * Use the same capitalisation as the developer's GitHub username, and plugin name. Include dashes or underscores.
    * Example: If Metro for Discord was a plugin, the plugin support file would be called: `_TakosThings.metro-for-discord.scss`
  * Import the plugin in `/src/components/betterdiscord/_plugin_support.scss`

### Updating or Adding Documentation
* Keep formatting consistent.
* Always use British English (that means putting the 'u' in 'colour').
