# SugarLabsPygameBaseGame
Working pygame that can run in Sugar's environment

A template for wrapping sugar around your pygame.

Runs
- On live-build(debian 10.13)(sugar:0.117), perfectly
- With ```python3 "name-of-main-file".py```, perfectly


Notes:
- Things that run with no issue with ```python3 "name-of-main-file".py```, cause issue on sugar. <br>
E.g. ```pygame.draw.rect(screen, GREEN, [115, 210, 70, 40], 10, border_radius=15)```.<br>
This line cause ```TypeError: rect() takes no keyword arguments```- tested on liv-build(debian 10.13)(sugar:0.117), but run with no issue with ```python3 "name-of-main-file".py```.
