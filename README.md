# ai-merge-resolve

[![npm version](https://img.shields.io/npm/v/ai-merge-resolve.svg)](https://www.npmjs.com/package/ai-merge-resolve)
[![npm downloads](https://img.shields.io/npm/dm/ai-merge-resolve.svg)](https://www.npmjs.com/package/ai-merge-resolve)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-merge-resolve)](https://github.com/lxgic-studios/ai-merge-resolve/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Stop manually resolving merge conflicts. Let AI figure out the best merge.

## Install

```bash
npm install -g ai-merge-resolve
```

## Usage

```bash
npx ai-merge-resolve conflicted-file.ts
# Prints resolved content

npx ai-merge-resolve conflicted-file.ts --write
# Writes resolved content back to file

cat conflicted-file.ts | npx ai-merge-resolve
# Read from stdin
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-w, --write` - Write resolved content back to the file

## License

MIT
