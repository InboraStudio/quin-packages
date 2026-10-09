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

Packages are built by `packages/build.py` in the Quin OS source tree. Each `.qpk` is a tar archive with a `package.json`; `index.json` lists every package with its SHA-256, which Quin OS checks before installing.
