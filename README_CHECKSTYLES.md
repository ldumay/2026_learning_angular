# Vérification du style

Le projet utilise des **tabulations** pour l'indentation, avec une largeur visuelle de
**4 espaces**.

- `.editorconfig` configure les éditeurs (`indent_style = tab`, `tab_width = 4`).
- `.prettierrc` configure Prettier (`useTabs: true`, `tabWidth: 4`).

## Formater

Depuis la racine du projet :

```powershell
npx prettier --write angular.json package.json tsconfig.json tsconfig.app.json tsconfig.spec.json .prettierrc ".vscode/*.json" "src/**/*.{ts,html,css,scss}" "_dev_note/*.md" README.md README_ANGULAR.md
```

## Contrôler

```powershell
npx prettier --check angular.json package.json tsconfig.json tsconfig.app.json tsconfig.spec.json .prettierrc ".vscode/*.json" "src/**/*.{ts,html,css,scss}" "_dev_note/*.md" README.md README_ANGULAR.md
```

Puis exécuter :

```powershell
npm run build
npm test
```
