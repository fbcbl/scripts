# Scripts

This will host the scripts that find useful for my android development setup.

## install-env

This script will try to install the following dependencies on your environment:
- Homebrew
- wget
- Android Studio
- Java 8
- Google Chrome
- ktlint
- git
- [adb-anim](https://medium.com/@danielhorowitzz/adb-anim-a-homebrew-tap-for-toggling-android-animations-69864c65f9a5)

- Slack (optional)
- Source Tree (optional)
- iTerm2 (optional)
- oh-my-zsh (optional)
- Zeplin (optional)
- Spotify (optional) - one only codes focused with music
- [Spectacle](https://www.spectacleapp.com/) (optional)

In addition it will try to setup a correct git configuration by asking your name and email, and create a private SSH key so that you don't have to authenticate everytime.

## screenshot

This script will make use of `adb` to take a screenshot of your connected phone and then it will resize it to 480x800 (so that the generated screenshot is not to big to use in PR descriptions.)

To run it just do `./screenshot`

## layoutb 

This script will enabled/disable the layout bounds on your phone. It takes one parameter that represents if it is enabled (`true`) or disabled (`false`)

Example:

- To enable `./layoutb true`
- To disable `./layoutb false`
