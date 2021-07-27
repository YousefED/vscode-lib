# vscode-lib

[![npm version](https://badge.fury.io/js/vscode-lib.svg)](https://badge.fury.io/js/vscode-lib)

This extracts several utility functions from VSCode / Monaco (VSCode "common" library).

The source is downloaded and built from: https://github.com/microsoft/vscode/tree/main/src/vs/base/common

# Usage

    npm install vscode-lib

Example code to access all exports from `https://github.com/microsoft/vscode/blob/main/src/vs/base/common/event.ts`:

    import { event } from "vscode-lib";

# How to build a new version

    npm install
    npm run update
    npm run build

# License

As the source code is extracted from https://github.com/microsoft/vscode, it's license (MIT) applies.
