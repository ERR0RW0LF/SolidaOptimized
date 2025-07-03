# Architecture

## Overview

There are two main part to the engine. The first one is the engine. The second one is the loader.

### Engine

The engine itself it is responsible for handling the modules and game.

### Loader

The loader this is the real part that is executed it informs the engine about what modules to load at the beginning and how the game integrates into the engine. It is also the part that should alow hot swapping of the game and engine parts.

[More on the loaders specific architecture](Loader.md)
