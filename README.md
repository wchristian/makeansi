makeansi.pl
===========

Converts images to a sequence of ansi rgb colour code 
escapes combined with unicode half block characters.

For a list of terminals that actually support the true
color ansi escape sequences, refer to this list:

   https://gist.github.com/XVilka/8346728

Usage:

   perl makeansi.pl some.png

Results should look like so:

![Ansi Marisa](http://aka-san.halcy.de/ansimari.png)

You can put the results in a text file and then just
cat it into the terminal for viewing, if you like.

Recommended console font: Droid Sans Mono

If you are a developer of a terminal emulator: Please
do implement these RGB colour code sequences, they're
really rad.


