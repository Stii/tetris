# tetris

Tetris game in rust from the book Rust Programming by example.

# Requirements

To get the game running, you need to install the following external libs:

``` bash
$ brew install sdl2 sdl2_image sdl2_ttf
```

This is for OS X only at the moment. Will in future add instructions for other 
platforms.

Once the dependencies are installed, you can run the game:


``` bash
$ cd /path/to/tetris
$ cargo run
```

And the game should start.

# TODO:

* Change background colour depending on the level
* Make quiting a slightly less final function (if you press escape, gone.)
* Add the funky Russian music :)
* Polish the look and feel of the game.
