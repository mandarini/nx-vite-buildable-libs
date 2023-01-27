# NX Vite Buildable Libs

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **This workspace has been generated by [Nx, a Smart, fast and extensible build system.](https://nx.dev)** ✨

## Installation

Run `npm install` to install all the dependencies.

## Reproduction

Running `npm run build` prints Typescript errors because path for `is-even` buildable library is not replaced with the build `dist` path. So Typescript is trying to check source files outside of the root source folder which results in bunch of `TS6059` errors.

## Further help

Visit the [Nx Documentation](https://nx.dev) to learn more.
