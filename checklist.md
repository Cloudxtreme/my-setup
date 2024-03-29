## Configure OS preferences, shortcuts, etc
- [ ] Update to the latest OSX patch
- [ ] Set new system password
- [ ] Turn on hard drive encryption
- [ ] Trackpad
	- [ ] Turn on 1 click touch
	- [ ] Enable three finger touch to drag (System Prefs > Accessibility > Trackpad > Shortcuts)
- [ ] Spotlight: change to `alt A` for Spotlight search
- [ ] Global Shortcuts (`System Preferences > Keyboard > Shortcuts`): 
  - [ ] `cmd shift +` for Window > Zoom
- [ ] App Shortcuts (`System Preferences > Keyboard > Shortcuts > App Shortcuts`)
  - [ ] Sketch: `Show Layers List` = `cmd 1`
  - [ ] Sketch: `Show Inspector` = `cmd 2`
- [ ] Dock
	- [ ] Move to left side
	- [ ] Check automatically show and hide
- [ ] Finder
	- [ ] Setup sidebar
	- [ ] Setup [default arrangement view](https://howchoo.com/g/mzuxyjqyzmy/how-to-set-the-view-options-for-all-finder-windows-in-os-x)
		- Arrange by: Name
		- Sort by: Name
		- Check Show item Info
		- Click `Use as Defaults`
	- [ ] Turn on [view hidden files](https://gist.github.com/jglovier/f87661ad2d10fa747ad6fcbbf7224305)
- [ ] Energy Saver: Turn off slightly dim display on battery power
- [ ] Security
	- [ ] Turn on FileVault disk encryption
	- [ ] Set to require password immediately
	- [ ] Turn on Firewall (?)

## Applications
- [ ] General
	- [ ] Go to App Store > Purchased and download all necessary
		- [ ] ByWord
		- [ ] Xcode
			- [ ] Also install [Command Line Tools](https://developer.apple.com/downloads/)
		- ~~Sketch~~ (not from App store anymore, download from site)
		- [ ] Slack
		- [ ] 1Password
		- [ ] TextExpander
		- [ ] DaisyDisk
		- [ ] etc
- [ ] [Dropbox](https://www.dropbox.com/install)
- [ ] [Chrome](http://www.google.com/chrome/)
	- [ ] Set to confirm on `Cmd Q` for Quit
	- [ ] Log in and sync bookmarks and extensions
	- [ ] Install [user style for GitHub.com](https://gist.github.com/jglovier/2dff3507d9ee007f6ce4)
- [ ] [Atom](http://atom.io)
- [ ] [GitHub Desktop](https://desktop.github.com/)
- [ ] [Sketch](http://www.sketchapp.com/)
- [ ] [Fantastical 2](https://flexibits.com/fantastical)
	- [ ] Check Appearance > Use color icon
- [ ] [Adobe Creative Cloud](http://www.adobe.com/creativecloud.html)
	- [ ] Photoshop
	- [ ] Illustrator
	- [ ] Acrobat
- [ ] [Bartender 2](https://www.macbartender.com/)
- [ ] Apple Mail (or [Nylas](https://nylas.com/))
	- [ ] Configure email accounts
- [ ] [Cloak](https://www.getcloak.com/)
- [ ] [Traktor 2](http://www.native-instruments.com/en/products/traktor/dj-software/traktor-pro-2/)

## CLI
- [ ] Xcode > install command line tools
- [ ] Install [iTerm2](https://www.iterm2.com/)
	- [ ] Load `.bash_profile`
	- [ ] Load `.gitconfig` contents into global `~/.gitconfig`
	- [ ] Load `.gitignore_global`
- [ ] Install [oh my zsh](http://ohmyz.sh/)
	- [ ] Load `.zshrc`
	- [ ] Install [Powerline patched fonts](https://github.com/powerline/fonts/)
- [ ] Set iTerm preferences
	- [ ] Install [Galaxy theme](https://github.com/jglovier/galaxy-theme-iterm)
	- [ ] Set text to:
		- Regular font: `14pt Roboto Mono for Powerline`
		- Non-ASCII font: `12pt Meslo LG L DZ Regular for Powerline`
- [ ] Install Ruby
	- [ ] Install rbenv via Homebrew: `brew install rbenv`.
	- [ ] Download a version of Ruby via rbenv (e.g., `rbenv install 2.2.3`). See <https://gorails.com/setup/osx/10.11-el-capitan>.
	- [ ] Make it the global version of Ruby: `rbenv global 2.2.3`.
- [ ] Install misc dependencies
	- [ ] Install Node via Homebrew: `brew install node`
	- [ ] Install Sass, Jekyll, and Rouge: `gem install sass jekyll rouge`.

## Atom
- [ ] Enable `atom` Terminal commands: from Atom.app, open the Atom menu and select *Install Shell Commands*
- [ ] Disable the `wrap-guide` package
- [ ] Install [favorite packages](https://atom.io/users/jglovier/stars):
	- [ ] [Fizzy syntax theme](https://atom.io/themes/fizzy) syntax package
	- [ ] [Wrap in tag](https://atom.io/packages/atom-wrap-in-tag)
	- [ ] [Selector to tag](https://atom.io/packages/selector-to-tag)
	- [ ] [Linter](https://atom.io/packages/linter) and [linter-stylelint](https://atom.io/packages/linter-stylelint)
	- [ ] [Autoclose HTML](https://atom.io/packages/autoclose-html)
	- [ ] [Compare files](https://atom.io/packages/compare-files)
	- [ ] [Less than slash](https://atom.io/packages/less-than-slash)
	- [ ] [Selector to tag](https://atom.io/packages/selector-to-tag)
	- [ ] [Merge conflicts](https://atom.io/packages/merge-conflicts)

## GitHub
- [ ] [Generate new SSH key](https://help.github.com/articles/generating-an-ssh-key/)
- [ ] [Generate an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) for Terminal to auth your GitHub account when 2FA is enabled.
- [ ] Download the [Strap](https://github.com/mikemcquaid/strap) setup script for GitHub's foundational development setup.
- [ ] Clone the `github/github` repository and run `script/osx-setup`, then `script/boostrap`.

## Code
- [ ] Setup `~/github`
- [ ] Setup `~/code/github-*`

## HospitalRun
- [ ] Clone [hospitalrun/hospitalrun-frontend](https://github.com/hospitalRun/hospitalrun-frontend/)
	- [ ] Run through [installation](https://github.com/hospitalRun/hospitalrun-frontend/#install)
	- [ ] Install [Ember inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) for Chrome

## Backup
- [ ] Configure TimeMachine and perform initial backup
  - [ ] Turn off, and set Cal reminder to perform manually each week

## Misc
- [ ] Install Fonts from backup fronts dir
- [ ] Download music from Apple Music
