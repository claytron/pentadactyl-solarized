# Pentadactyl Solarized Theme

This is a color scheme for the incredible [Pentadactyl][penta] add-on
for [Firefox][ff]. It uses the color palette [Solarized][solar],
designed by Ethan Schoonover.

This color scheme aims to be one of the most complete color schemes
available. Even the help has been styled! If you have a suggestion or
find any bugs with the current implementation, please enter an issue in
the tracker:

https://github.com/claytron/pentadactyl-solarized/issues

NOTE: The dark color scheme has not yet been implemented. Once the light
scheme has been finalized, the dark scheme will be created.

## Install

To install this color scheme, copy it into your `~/.pentadactyl/colors`
folder, creating it if it doesn't exist:

    $ mkdir -p ~/.pentadactyl/colors
    $ cp solarized-*.penta ~/.pentadactyl/colors/.

Then change your default theme by adding the following to your
`~/.pentadactylrc`

    colorscheme solarized-light

Or if you prefer the dark version

    colorscheme solarized-dark

Then re-source your `.pentadactylrc`, or restart your browser to see the
changes go into effect.

    :source ~/.pentadactylrc

## Screenshots

### Statusline Normal

![Statusline Normal](http://i.imgur.com/4ZSVe.png)

### Statusline Secure

![Statusline Secure](http://i.imgur.com/popfu.png)

### Statusline Extended

![Statusline Extended](http://i.imgur.com/jlk4K.png)

### Statusline Broken

![Statusline Broken](http://i.imgur.com/2pDAE.png)

### Hints

![Hints](http://i.imgur.com/XSRyG.png)

### Completions

![Completions](http://i.imgur.com/bnp85.png)

### Buffers

![Buffers](http://i.imgur.com/9yKSl.png)

### Help

![Help](http://i.imgur.com/G3g5n.png)

## Notes

This theme clears out all highlighting settings before applying its own
in order to avoid bleed over from other themes.

If there are any issues, you can report them here:
https://github.com/claytron/pentadactyl-solarized/issues

## Changelog

### 1.0b1

- Added this changelog
- Finalized the light theme
- Made sure that every color in `:highlight` is using the Solarized
  palette
- Change buttons on the `:downloads` dialog so that they are more
  readable
- Added `HelpXML*` styles so that code blocks match Solarized in the
  help
- Links in the `:help` section are now a Solarized color, but no
  `visited` state will appear
- Finished out all the styles for the help section

### 1.0a2

- Fix `:downloads` screen so that `LinkInfo` is readable

### 1.0a1

- Initial release of the light theme
- Added README and screenshots


[ff]: https://www.mozilla.org/en-US/firefox/fx/
[penta]: http://5digits.org/pentadactyl/
[solar]: http://ethanschoonover.com/solarized
