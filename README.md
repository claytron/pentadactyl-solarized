# Pentadactyl Solarized Theme

This is a color scheme for the incredible [Pentadactyl][penta] add-on
for [Firefox][ff]. It uses the color palette [Solarized][solar],
designed by Ethan Schoonover.

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

## Notes

This theme clears out all highlighting settings before applying its own
in order to avoid bleed over from other themes.

If there are any issues, you can report them here:
https://github.com/claytron/pentadactyl-solarized/issues


[ff]: https://www.mozilla.org/en-US/firefox/fx/
[penta]: http://5digits.org/pentadactyl/
[solar]: http://ethanschoonover.com/solarized
