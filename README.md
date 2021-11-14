# react-jsconfig.json
go to the react component after click on a component

jsconfig.json:
```
{
  "compilerOptions": {
    "module": "commonjs",
    "target": "es2017",
    "jsx": "react",
    "allowSyntheticDefaultImports": true,
    "baseUrl": ".",
    "paths": {
      "@/*":["src/*"],
      "root/*": ["./*"]
    }
  },
  "exclude": [
    "node_modules",
    "dist",
    ".next",
    ".cache",
    "bundles",
    "out"
  ],
  "include": [
    "build/**/*",
    "server/**/*",
    "e2e/**/*",
    "pages/**/*",
    "src/**/*",
    "stories/**/*"
  ]
}
```
