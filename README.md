# tsx-demo

Demo of using [tsx](https://github.com/privatenumber/tsx) to run a nodejs application written in Typescript.

### Details

- Runtime: node v22
- Format: ESM
- Compiler: `tsx`
- Watch mode: `tsx`
- Package manager: `yarn` (modern)
- Node linker: Plug'n'Play

### Installation

- Load the right version of node (e.g., `nvm use`)
- If this is your first time using `yarn` with this particular download of node, run `corepack enable`
- Run `yarn`
  - You may have to follow instructions on getting your IDE to play nice with Yarn PnP by following their [guide](https://yarnpkg.com/getting-started/editor-sdks)
  - If you're using VSCode or Cursor, everything should work out of the box, except you might need to install the [ZipFS](https://marketplace.visualstudio.com/items?itemName=arcanis.vscode-zipfs) extension

### Getting started

- For developing with auto-restart upon file change, `yarn dev`
- To run once, `yarn start`
- You can manually demo `esbuild` as well for compiling (run `yarn build`), since that's what `tsx` uses under the hood, but it's not strictly necessary
