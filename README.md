# Typescript Node Boilerplate

Boilerplate setup for running Node.js + Typescript

This comes with sensible default configs for prettier & eslint, and uses `esbuild` for running locally. Typechecking is handled in a separate process on build.

| Script        | Description                                                                                                                                                                                        |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `start`       | Runs the `index.ts` script. This uses `esbuild` which is much faster than `tsc`, but `esbuild` does not do typechecking. For running locally it's easier to do typechecking in a separate process. |
| `build`       | Compiles the project using `tsc` which also performs type checking.                                                                                                                                |
| `build:watch` | Compiles the project using `tsc` in watch mode                                                                                                                                                     |
| `lint`        | Runs ESLint                                                                                                                                                                                        |
| `prettier`    | Runs Prettier                                                                                                                                                                                      |
