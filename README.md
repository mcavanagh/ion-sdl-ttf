# ion-sdl_ttf
Ion bindings for SDL_ttf functions

# Usage

Copy the 'sdl_ttf' folder to your `$IONHOME/system_packages` directory or add it to your `$IONPATH`

Then in your .ion file:

```
import sdl_ttf { ... };

...

font := TTF_OpenFont(font_path, font_size);

```

These bindings have a dependency on the `sdl` package, which is currently in Ion's system_packages dir by default.
