# Modified Passion Theme for OhMyZsh

An oh-my-zsh theme, modified from the [original](https://github.com/ChesterYue/ohmyzsh-theme-passion) by ChesterYue

## Introduction

![passion](https://raw.githubusercontent.com/AbdullahEhsan/passion-theme-ohmyzsh/master/passion.gif)

* real time prompt.
* command running time cost prompt.
* command running error hint.

## Usage

REF: [Oh-My-Zsh External themes](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes)

## Troubleshooting

### macOS

passion.zsh-theme depends on cmd ```gdate``` to get current time in milliseconds which is not installed by default in macOS.

to get ```gdate``` by running ```brew install coreutils;```

## Installation

1. Clone
```
git clone https://github.com/AbdullahEhsan/passion-theme-ohmyzsh.git $ZSH_CUSTOM/themes/passion-modified
```
2. Symlink
```
ln -s $ZSH_CUSTOM/themes/passion-modifed/passion.zsh-theme $ZSH_CUSTOM/themes/passion-modified.zsh-theme
```
3. Set in ~/.zshrc (replace existing)
```
ZSH_THEME="passion-modified"
```
