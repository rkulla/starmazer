Starmazer is a little terminal based maze game I wrote in the 90s.

# Playing starmazer

Start it up in the console:

    $ ./starmazer

Make sure numlock on your numeric keypad is turned off!

To move your "spaceship" (X) around press:

    1/END = down/left
    2 = down
    3/PgDn = down/right
    4 = left
    5 = does nothing
    6 = right
    7/HOME = up/left
    8 = up
    9/PgUp = up/right

To shoot your "probe launcher" press:

    a = left
    s = up
    d = down
    f = right
    z = up/left
    x = up/right
    c = down/left
    v = down/right


Your goal is to probe the wormholes (@). There are two ways:
    1) Move your spaceship onto it
    2) Shoot probes (+) into them.

Each time you successfully probe a wormhole, more stars are added to the screen. If you run into a
star, it damages your ship and eventually you die.

There are 30 levels total in starmazer.

(Note: if 30 levels becomes to easy for you you can change the value for "level_max" in starmazer.c
to whatever number you like to add more levels!)

You can press CTRL-C at any time to quit starmazer.
