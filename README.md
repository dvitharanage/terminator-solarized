# Solarized terminator colors

A color theme for [terminator](http://www.tenshu.net/terminator/) using Ethan Schoonover’s [Solarized color scheme](http://ethanschoonover.com/solarized).

## Repositories
  * This theme as a single repository: [/ashleyblackmore/terminator-solarized](https://github.com/ashleyblackmore/terminator-solarized)
  * The main solarized repository: [/altercation/solarized](https://github.com/altercation/solarized)

## Files
  * `config` -  solarized theme for terminator (tweaked by [ashleyblackmore](https://github.com/ashleyblackmore))

## Usage
Install the terminator configuration file:

    # cp config ~/.config/terminator/

IMPORTANT: Modify the defaults stanza within the terminator configuration file to select your default(s). For example, change the profile line from "default" in the following:

    [layouts]
      [[default]]
        [[[child1]]]
          type = Terminal
          parent = window0
          profile = solarized-dark
        [[[window0]]]
          type = Window
          parent = ""

Palettes are as follows:

    [profiles]
      [[default]]
        #palette = "#073642:#dc322f:#859900:#b58900:#268bd2:#d33682:#2aa198:#eee8d5:#002b36:#cb4b16:#586e75:#657b83:#839496:#6c71c4:#93a1a1:#fdf6e3"
        #foreground_color = "#eee8d5"
        #background_color = "#002b36"
        #cursor_color = "#eee8d5"

      [[solarized-dark]]
        palette = "#073642:#dc322f:#859900:#b58900:#268bd2:#d33682:#2aa198:#eee8d5:#002b36:#cb4b16:#586e75:#657b83:#839496:#6c71c4:#93a1a1:#fdf6e3"
        foreground_color = "#eee8d5"
        background_color = "#002b36"
        cursor_color = "#eee8d5"

      [[solarized-light]]
        palette = "#073642:#dc322f:#859900:#b58900:#268bd2:#d33682:#2aa198:#eee8d5:#002b36:#cb4b16:#586e75:#657b83:#839496:#6c71c4:#93a1a1:#fdf6e3"
        background_color = "#eee8d5"
        foreground_color = "#002b36"
        cursor_color = "#002b36"
