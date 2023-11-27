# TypeScript Blank

Generate tsconfig.json:
`tsc --init`

NPM scripts:

```json
"scripts": {
    "dev": "nodemon src/main.ts --conifg nodemon.json",
    "build": "tsc -p .",
    "start": "node dist/main.js"
}
```
