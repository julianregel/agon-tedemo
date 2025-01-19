This program contains two BASIC demos
of the Tile Engine.

The first demo, MARIO.BAS, demonstrates
per-pixel horizontal scrolling. This 
demo is designed to run in a 
double-buffered mode. The demo performs
a CLS to draw a blank blue background
before the tiles are drawn. 
In non-double buffered mode, the CLS
and tile drawing causes a flickering
effect which is expected (but not nice)
behaviour.

The second demo, ISLAND.BAS, is very
similar to MARIO.BAS, but demonstrates
vertical scrolling. This demo also
draws the entire screen of tiles, so 
does not require the CLS command and
does not have the flickering issue as
described above.

 