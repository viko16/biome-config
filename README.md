# @viko16/biome-config

A comprehensive Biome configuration package for JavaScript & TypeScript projects.

## Installation

```bash
npm install @viko16/biome-config @biomejs/biome --save-dev
```

## Usage

Create a `biome.json` in your project root:

```json
{
  "extends": "@viko16/biome-config"
}
```

Add scripts to your `package.json`:

```json
{
  "scripts": {
    "check": "bunx biome check --write"
  }
}
```

## License

MIT
