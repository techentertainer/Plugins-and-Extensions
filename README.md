<div align="center">
  <img src="https://github.com/techentertainer/Plugins-and-Extensions/blob/master/developer.jpg">
</div>
<br/>
<div align="center">

A curated list of delightful packages/tools/extensions/resources/plugins to increase work effort and ease. Watch this repo to get updates on the new ones in the community.

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
</div>
<br/>

# Table of Contents

- [Mac OS essentials](#mac-os-essentials)
  - [iTerm2](#iterm2)
  - [zsh for Terminal](#zsh)
  - [Insomnia](#insomnia)
- [General Extensions](#general-extensions)
  - [Prettier](#prettier)
  - [Flow](#flow)
  - [ESLint](#eslint)
  - [Editor Config](#editorconfig)
  - [Wakatime](#wakatime)
- [Atom editor extensions](#atom-editor-extensions)
  - [Nuclide](#nuclide)
- [VSCode editor extensions](#vscode-editor-extensions)
  - [Todo Highlight](#todo-highlight)
  - [GitLens](#git-lens)
  - [Settings Sync](#settings-sync)
  - [Python](#python)
  - [npm Intellisense](#npm-intellisense)
- [Google Chrome extensions](#google-chrome-extensions)
  - [Octotree](#octotree)
  - [Last Pass](#last-pass)
  - [GitHub File Icons](#github-file-icons)
  - [React Devtools](#react-devtools)
  - [Redux Devtools](#redux-devtools)
- [Contributing](#contributing)
  
# Mac OS Essentials

Extensions for your Mac setup to increase productivity.

### iTerm2

[iTerm2](https://www.iterm2.com) - macOS terminal replacement. Features include `split panes`, `mouseless copy`, `paste history`, `themes` and many more. Check it out [here](https://www.iterm2.com/features.html). <br/>

Split panes:
<div align="center">
  <img src="https://github.com/techentertainer/Plugins-and-Extensions/blob/master/iterm.png">
</div>

### zsh

[zsh](http://ohmyz.sh) - Make your terminal feel good. Personally, I would never be productive enough without it. Makes you fast, not wasting time on write every minute commands like `git status` again and again, writing the long line to run the  `Django server`, etc etc. (Must have)

zsh works best with the community-developed [customisable themes](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes) making the terminal colorful according to you.
But its main power lies in the [plugins](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins). Some of its best are [git](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#git), [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) etc.
  - I use [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) with [iTerm2](https://www.iterm2.com) and [Solarised Dark](https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized) color scheme, with git and autosuggestion at work below.
  
<div align="center">
  <img src="https://github.com/techentertainer/Plugins-and-Extensions/blob/master/zsh-git-autosuggest.png">
</div>

## Insomnia

[Insomnia](https://insomnia.rest) - Debug APIs now like a human should, by viewing entire transaction record, code snippets generation for requests in multiple languages, even write GraphQL queries. (Must have)

<div align="center">
  <img src="https://insomnia.rest/static/main-ac0a1732afac19acce5ad6825595c3bb-5c808.png">
</div>

# General Extensions

Most of the tools in this category, in dev terms pertain to auto-formatting, auto-editing and all other auto-* things, because we developers hate to format our code but we need it `pretty looking` when we go back to it.

In case the awesome nirvana that is linting has not yet been unleashed upon you:
> lint was the name originally given to a particular program that flagged some suspicious and non-portable constructs (likely to be bugs) in C language source code. The term is now applied generically to tools that flag suspicious usage in software written in any computer language.

### Prettier

[Prettier](https://prettier.io) - Linter, Formatter and Pretty printer for JS, CSS, Graphql. Upcoming: Java, Python etc. (Must have)

<div align="center">
   <img src="https://github.com/prettier/prettier-atom/raw/master/prettier-demo.gif">
</div>

- [VSCode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Atom](https://github.com/prettier/prettier-atom)
- [Sublime Text](https://packagecontrol.io/packages/JsPrettier)

### Flow

[Flow](https://flow.org) - Facebook's JS Static Type Checker with Realtime Feedback in your editor. Now know the edge cases and build faster and more confidently. (Must have)

- [VSCode](https://marketplace.visualstudio.com/items?itemName=flowtype.flow-for-vscode)
- For Atom, you can use [Nuclide](#nuclide), which comes with much more tools. For a lighter package, use [IDE-Flowtype](https://atom.io/packages/ide-flowtype).
- [Sublime Text](https://packagecontrol.io/packages/Flow)

### ESLint

[ESLint](https://eslint.org) - Linting utility for JS, eg. finding out unused code, errors while typing, formatting and all.

- [VSCode](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Atom](https://atom.io/packages/linter-eslint)
- [Sublime Text](https://github.com/SublimeLinter/SublimeLinter-eslint)

### Editorconfig

[Editorconfig](https://editorconfig.org) - Main coding styles across different IDEs and editors. 

- [VSCode](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Atom](https://github.com/sindresorhus/atom-editorconfig)
- [Sublime Text](https://github.com/sindresorhus/editorconfig-sublime)
- [PyCharm and Android Studio](https://plugins.jetbrains.com/plugin/7294-editorconfig)
- [Xcode](https://github.com/MarcoSero/EditorConfig-Xcode)

### Wakatime

[Wakatime](https://wakatime.com) - Quantify your programming and know how much time are you spending on what projects, languages, per day with intuitive statistics.

<div align="center">
  <img src="https://github.com/techentertainer/Plugins-and-Extensions/blob/master/wakatime.png">
</div>
Wakatime has support for 30+ IDEs, including Vim, Xcode, Sketch, Eclipse.

# Atom editor extensions

### Nuclide

[Nuclide](https://nuclide.io) - Unified developer experience for development on [Web](https://nuclide.io/docs/platforms/web/), [iOS](https://nuclide.io/docs/platforms/ios/), [React Native](https://nuclide.io/docs/platforms/react-native/).
This plugin has built-in support for [Flow](#flow), connecting to Remote Server, languages like Python, Swift, Objective-C, GraphQL, C++, PHP and more.

# VSCode editor extensions

### TODO Highlight

[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) - Highlight TODO,FIXME or any annotations within your code. Add a comment with such annotations, so that you don't forget what to fix or what feature to add. (Must have)

<div align="center">
  <img src="https://github.com/wayou/vscode-todo-highlight/raw/master/assets/material-night-eighties.png">
</div>

### Git Lens

[Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Visualize code authorships, jumping into histories of the code, diffing between branches. (Must have)

### Settings Sync

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) - Synchronise all your VSCode settings, preferences across different machines in a go.

### Python

[Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - Intellisense, snippets, code runner, linting, code formatting, unit testing.

### npm Intellisense

[npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - Autocompletes npm modules in import/require statement.

<div align="center">
  <img src="https://github.com/ChristianKohler/NpmIntellisense/raw/master/images/auto_complete.gif">
</div>

# Google Chrome extensions

### Octotree

[Octotree](https://chrome.google.com/webstore/detail/octotree/bkhaagjahfmjljalopjnoealnfndnagc) - Code tree for GitHub. Now you won't have to navigate folder by folder to get to a specific file on GitHub, do it like in your editor.

<div align="center">
  <img src="https://github.com/techentertainer/Plugins-and-Extensions/blob/master/octotree.png">
</div>

### Last Pass

[Last Pass](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd) - Saves your password securely and gives it access on your browser and mobile. Save almost any other information as well.

### GitHub File Icons

[GitHub File Icons](https://chrome.google.com/webstore/detail/github-file-icon/ficfmibkjjnpogdcfhfokmihanoldbfe?hl=en) - File icons for GitHub.
See the [Octotree](#octotree) view to see all files, but you won't know their type unless you read them. With this extension, it becomes so live and graphic.

<div align="center">
  <img src="https://github.com/techentertainer/Plugins-and-Extensions/blob/master/gthub-file-icon.png">
</div>

### React Devtools

[React Devtools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) - Official React debugging tool made by Facebook. Lights up `blue` on any production website using React, then inspect its components, state, props, functionality, and endless powerful features. (Must have)

<div align="center">
  <img src="https://github.com/facebook/react-devtools/raw/master/images/devtools-full.gif">
</div>

### Redux Devtools

[Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en) - Inspect your Redux state, dispatch actions, do `time travel` of your app, and many more. (Must have)

<div align="center">
  <img src="https://github.com/techentertainer/Plugins-and-Extensions/blob/master/redux.png">
</div>

# Contributing

Found out a plugin missing here, or did you find a mistake. Suggest an edit by making a PR. Watch this repository to subscribe to updates if any, so that you don't miss the new ones.
