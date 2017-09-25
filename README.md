## t3C and t3

`t3C` and `t3` are [Bash](https://www.gnu.org/software/bash/) script (see [Wikipedia:Bash\_(Unix_shell)](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29) for more info) implementations of the usual [Tic-Tac-Toe (or Noughts-and-Crosses)](https://en.wikipedia.org/wiki/Tic-Tac-Toe) [paper-and-pencil game](https://en.wikipedia.org/wiki/Paper-and-pencil\_game).  

`t3C` is for x-terminals that support color while `t3` is for x-terminals that don't support color.  Both bash scripts are two-player implementations of tic-tac-toe.

To play: at the command line, within the directory containing the script, issue the command:
```bash
bash t3C
```
(or simply `t3C` if the this script is on your path of executables, i.e., if `echo $PATH` shows a list of directories that includes the directory containing the bash script `t3C`.  To make sure, you can copy these two bash scripts to your `$HOME/.local/bin directory` then add the `.local/bin` directory to your `PATH`, e.g., at the command line `PATH=$PATH:$HOME/.local/bin/`).

A screenshot (partly edited) of a `t3C` tic-tac-toe game session is given below.  
![tic-tac-toe: The Game!](./t3C-all.gif)

## Acknowledgements
My sincerest gratitude to Brian Fox for [Bash](https://www.gnu.org/software/bash/); Machtelt Garrels for the book [Bash Guide for Beginners](http://tldp.org/LDP/Bash-Beginners-Guide/html/Bash-Beginners-Guide.html), Vivek Gite for the book [Linux Script Shell Tutorial](http://www.freeos.com/guides/lsst/), and Steve Parker for the [Unix/Linux Shell Cheatsheet](http://steve-parker.org/sh/cheatsheet.pdf); Eddie K&ouml;hler for [Gifsicle](https://www.lcdf.org/gifsicle/), [ImageMagick](https://www.imagemagick.org/), and Dmitry Groshev, Mark Tyler, Xiaolin Wu et. al. for [mtPaint].  Much thanks, too, to the [Debian Project](https://www.debian.org) for the Debian 8 (Jessie) GNU/Linux OS and [GitHub](https://github.com) for its generosity in providing space for [this project](https://github.com/justineuro/tic-tac-toe). 

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title"><b>tic-tac-toe</b></span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/justineuro/" property="cc:attributionName" rel="cc:attributionURL">Justine Leon A. Uro</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/justineuro/mdginabc2svg" rel="dct:source">https://github.com/justineuro/tic-tac-toe</a>