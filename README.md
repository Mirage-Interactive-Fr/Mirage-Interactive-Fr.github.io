# Mirage Interactive documentation

This repository hosts the generated PerfChecker documentation on GitHub Pages.
The development site is intended for
[mirage-interactive-fr.github.io/dev/](https://mirage-interactive-fr.github.io/dev/).

Documentation sources, issues and contributions belong in
[PerfChecker.jl](https://github.com/Mirage-Interactive-Fr/PerfChecker.jl/tree/release/v1.0.0-rc4).
Its qualification workflow publishes the exact validated site to this repository
using a dedicated deploy key.

Configure Pages to serve the root of the `gh-pages` branch. Documenter creates
the site root redirect and version selector when the first qualified site is
published. Additional documentation projects may later use separate paths.

See [deployment setup](https://github.com/Mirage-Interactive-Fr/PerfChecker.jl/blob/release/v1.0.0-rc4/website/DEPLOYMENT.md).
