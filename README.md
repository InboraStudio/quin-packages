# Quin OS Packages

The package repository for [Quin OS](https://github.com/InboraStudio). Install from the **Package Manager** app, or in Terminal:

```
pkg update
pkg install blockball
```

| Package | Version | Kind | What it is |
|---|---|---|---|
| **Block Ball** (`blockball`) | 1.0.0 | app | A brick breaker with power-ups, combos and five level patterns. |
| **Block Drop** (`blockdrop`) | 1.0.0 | app | Falling blocks with a ghost piece, hold, combos and levels. |
| **SciCalc** (`scicalc`) | 1.0.0 | app | A scientific calculator that shows the answer as you type. |
| **Vulkan Cube** (`vulkan-cube`) | 1.0.0 | app | Spinning 3D shapes drawn through Quin OS's Vulkan. |
| **Hello Terminal** (`hello-terminal`) | 1.0.0 | terminal | A colourful tour of what the Quin terminal can draw. Run: hello-terminal |
| **cowsay** (`cowsay`) | 1.0.0 | terminal | A cow (or Tux, a cat, a robot) says whatever you like. Run: cowsay hi |
| **fortune** (`fortune`) | 1.0.0 | terminal | A random saying about code and making things. Run: fortune |
| **weather** (`weather`) | 1.0.0 | terminal | Today's weather and a 3-day forecast, right in Terminal. Run: weather Tokyo |
| **todo** (`todo`) | 1.0.0 | terminal | A to-do list that lives in Terminal. Run: todo add water the plants |
| **pomo** (`pomo`) | 1.0.0 | terminal | A focus timer with a big countdown, a chime and a notification. Run: pomo |
| **2048** (`2048`) | 1.0.0 | terminal | Slide the tiles, join equal numbers, reach 2048. Run: 2048 |
| **matrix** (`matrix`) | 1.0.0 | terminal | Digital rain like the film, in any colour. Run: matrix |
| **hexview** (`hexview`) | 1.0.0 | terminal | Browse any file as hex, with a text column and number inspector. Run: hexview FILE |
| **musicviz** (`musicviz`) | 1.0.0 | terminal | A live spectrum of the music playing, right in the Terminal. Run: musicviz |
| **Quincraft** (`quincraft`) | 1.4.0 | app | A complete voxel sandbox: endless worlds, caves, survival, crafting, mobs and day and night. |
| **Voice Recorder** (`voice-recorder`) | 1.0.0 | app | Record your voice, keep it as a WAV file and listen to it again. |
| **HD Audio Driver** (`hda-audio`) | 1.0.0 | driver | Sound for computers with Intel High Definition Audio -- nearly every PC since 2005. |
| **Lua for Quin Studio** (`lang-lua`) | 1.0.0 | Studio extension | Lua colours, an outline, Ctrl+R to run, and a Hello Lua project for Quin Studio. |
| **Python for Quin Studio** (`lang-python`) | 1.0.0 | Studio extension | Python colours and an Outline for Quin Studio (no interpreter on Quin OS yet). |
| **Web Languages for Quin Studio** (`lang-web`) | 1.0.0 | Studio extension | JavaScript, JSON and CSS colours for Quin Studio. |
| **Shell and Config Files for Quin Studio** (`lang-config`) | 1.0.0 | Studio extension | Shell scripts (Ctrl+R runs them), Makefiles, YAML, TOML and SQL in Quin Studio. |

Packages are built by `packages/build.py` in the Quin OS source tree. Each `.qpk` is a tar archive with a `package.json`; `index.json` lists every package with its SHA-256, which Quin OS checks before installing.
