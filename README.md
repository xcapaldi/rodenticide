# 3i

![3i](3i_resized.png)

Opinionated and advanced configuration for the i3 window manager with smarter defaults.

## Philosophy

i3 and tiling window managers in general take care of window layout and maximize your available screen space.
i3 is designed to act as a modal window manager with an interface similar to vim.
However having used i3 for quite some time, I found myself making many keybindings in the default mode.
This required me to memorize tons of bindings for my window manager on top of those I've learned for all the other tools I use.
In addition, I realized while reading the excellent i3 user guide that I had not taken advantage of all the available features.
I wanted to write a configuration which is not only educational but lays down a framework for the advanced features of i3.

3i emphasizes three pillars:

1. Maximal focus
2. Minimal memorization
3. Minimal dependencies

The main goal is to have a decent default configuration that illustrates a variety of features available in i3.
I assume that if you are using i3, you are quite happy modifying a configuration file to suite your needs and that is fully expected here.
If you aren't about that life, I recommend using vanilla Gnome actually.
The design philosophy is also about a highly focused desktop environment with much less configuration.

![Screenshot of environment](screenshot.png)

### What 3i is not

This is not an eyecandy configuration.
I encourage you to rice it as you see fit.
That is just not the purpose of this configuration as I've written it.

## Configs

#### A note on format

All the configurations were written in vim and use the vim folding functionality to organize.

If you are using vim, you can enable folding by typing :set foldmethod=marker
Then you can close folds with zc and open with zo.

### basic

This configuration is a slight modification of the default configuration.
The setup is made slightly more modal but remains otherwise unchanged.
This is good if you still want to handle the configuration fully yourself but you'd like to use the formatting from 3i.

### advanced

This configuration includes a helpful mode for audio.
It add details for the scratchpad configuration.
It suggests colors for improved focus.
This take advantage of most of the features available in i3 for a general configuration.

## FAQ

### Why the name 3i?

I just played Nier Automata.
The main characters in the game are androids and classified by a number representing their model and a letter representing their role.
3i is just following the naming convention from the game.
i3 was inspired by wmii which stood for window manager improved(squared).
I assume i3 stands for improved(cubed).
So 3i is the android model 3 whose role is improvement.
I know.
It's hella cheesy.

### Did you learn to draw an anime girl just for this project?

Yes.

### I want to draw anime girls too. Where can I learn?

I used [this video](https://www.youtube.com/watch?v=2GbSCdoyO_I) and then I modified the hair using [this guide](https://www.animeoutline.com/how-to-draw-anime-and-manga-hair-female/).
