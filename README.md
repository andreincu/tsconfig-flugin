# My tsconfig base configuration for working on plugins for Figma.

Add the package to your `"devDependencies"`:

```sh
npm i -D flugin-tsconfig
```

Extend your `tsconfig.json`:

```json

"extends": "flugin-tsconfig/tsconfig.json"

```

---

## Configuration

```json
{
    "exclude": ["node_modules"],
    "compilerOptions": {
      "module": "ESNext",
      "target": "ES2017",
      "moduleResolution": "bundler",
      "declaration": true,
      "strict": true,
      "noEmit": true,
      "skipLibCheck": true,
      "esModuleInterop": true,
      "verbatimModuleSyntax": true,
      "isolatedModules": true,
      "resolveJsonModule": true,
      "removeComments": false,
      "composite": false,
      "noErrorTruncation": true,
      "forceConsistentCasingInFileNames": true
    }
  }
```
