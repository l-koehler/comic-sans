#### Alacritty

* Download [Comic Mono](https://dtinth.github.io/comic-mono-font/ComicMono.ttf) and [Comic Mono Bold](https://dtinth.github.io/comic-mono-font/ComicMono-Bold.ttf).
* Install both fonts.
* Locate the config file (~/.config/alacritty/alacritty.yml on Linux,
  C:/Users/***{username}***/AppData/Roaming/alacritty/alacritty.yml)
* Add the contents of the alacritty.yml file from here to the config file.

Note:
You could use regular Comic Sans, but it looks *really* terrible.
Because alacritty can only handle monospaced fonts, you will either
have characters like M overlap or have huge gaps between small
characters like 'l'.
If you want to do this, replace both fonts in the yml with "Comic Sans MS" and
uncomment the offset. Change the 10 to get a non-terrible compromise between
gaps and overlaps.