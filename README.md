# Fira for Powerline

## About
This repository hosts a modified version of [Fira Mono](https://mozilla.github.io/Fira/), which has been patched to include the requisite Powerline symbols for use with various Vim status/tab bars (Powerline, Lightline, Airline, etc). See screenshot below for an example.

## Usage in gvim
To set the font for use in MacVim/gvim:

    if has('gui_running')
      set guifont=Fira\ Mono\ for\ Powerline:h15
    endif


(Adjust the font size (here set as h15) to yr liking.)

## License and other info
This typeface is licensed under the SIL Open Font License (OFL), as per the original font files. Please see the [master Fira repository on GitHub](https://github.com/mozilla/Fira) for license and further information.

## Screenshot
![Screenshot](fmp-screenshot.png)
