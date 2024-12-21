# Node-Typescript
A sample node and typescript package boilerplate

## Setup

### create folder
```bash
mkdir project-name
cd project-name
```

### npm initialization
```bash
npm init --y
```

### npm dependency installation
```bash
npm install typescript
```

### create typescript initialization add default config
```bash
npx tsc --init
```

or

### create manual typescript config
create tsconfig.json file and add the below config 
```
{
  "include": ["src/**/*"],
  "compilerOptions": {
    "target": "ESNext",
    "module": "commonjs",
    "outDir": "./dist",
    "strict": true,
    "declaration": true,
    "declarationMap": true,
    "skipLibCheck": true
  }
}
```

### build the package
```bash
npm run build
```
