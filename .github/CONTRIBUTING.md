# Contributing

## Issues
* Disable BetterDiscord plugins and addon themes before opening an issue. 
* Use the provided *Bug report* template when opening a new Issue.
  * You may delete the placeholder help text under each header if you wish.
  * You may remove the *Steps to reproduce* section if you don't need it.
* Please don't 'bulk report' unrelated issues in the same Issue.
* Please don't report a new issue in the thread of an existing issue if it is unrelated.
* Please don't open an issue if your problem relates directly to BetterDiscord or if a BetterDiscord plugin or addon theme is causing a conflict with this theme. 
* Search through existing issues before adding a new *Feature request*. These issues are tagged with the `Feedback` label.

## Developing
### Requirements
* An editor (like [Visual Studio Code](https://code.visualstudio.com/))
* [Git](https://git-scm.com/)
* [Node](https://nodejs.org/en/)
* [Editorconfig](https://editorconfig.org/) plugin if your editor doesn't support it natively (VSCode needs a [plugin](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig))

### Setup
* Clone the repository `git clone https://github.com/TakosThings/Metro-for-Discord`
* Run `npm i`

### Development
* Use `npm run watch` to automatically compile the themes as you work

## Contributing Changes
* Clone/rebase the repo and make your changes in a new branch
* Open an issue using the *Change proposal* template to discuss your changes
* Make sure your editor is obeying `.editorconfig`
  * To test: Try adding a bunch of superfluous spaces after a line of CSS and then save. The spaces should be automatically removed.
* Don't worry about updating `README.md`, `CHANGELOG.md` or committing the `/dist/` directory
* Submit a PR, referencing the discussion issue

### Things to know
* All development and testing is done using BeautifulDiscord, which can auto-reload the theme as you work
