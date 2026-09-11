# use-fluent

Small typed hooks: debounce, localStorage, media query, toggle

## Getting started

```bash
npm install
npm test
```

## What it does

- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe
- Tiny: no dependencies besides React

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## License

MIT. Do whatever you want.
