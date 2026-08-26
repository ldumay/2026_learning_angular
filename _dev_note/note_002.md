# Angular

---
_**Partie 1 **_
---

## Qu'est ce que Angular ?

Angular est un framework JavaScript frontend pour la construction d'interface web moderne.

## Pourquoi ?

Pour des application web complexe, intrégrant le code déclaratif au lieu du simple code impératif de JavaScript.
En résumé :
- Simplication du processus de développement
- Créationd'application modulaire
- Orienté objet.
- Basé sur le Typescript

## L'évolution de Angular

### AngularJS - Simple librairie JavaScript

Durée de vie le libraire : **2010** à **2022**. 
[plus d'infos](https://en.wikipedia.org/wiki/AngularJS).

### Angular 21 - Framework modern

Durée de vie du framework : **2016** à **Aujourd'hui**
[plus d'infos](https://en.wikipedia.org/wiki/Angular_(web_framework)).

Sortie en version 2 en 2016, **la version actuelle est la 22**.

Version majeurs :
- **2016 - Angular 2** - réécriture total de Angular JS vers Angular
- **2017 - Angular 5** - HTTP, guards & resolvers, support for web apps and Matrial Design
- **2018 - Angular 7** - Updating : performans, Material, CDK, Accessibility, TypeScript 3.1 support and RxJS
- **2019 - Angular 8** - Dynamic imports for lazy routes, Web workers, TypeScript 3.4 support, and Angular Ivy as an opt-in preview
- **2020 - Angular 10** - New Date Range Picker (Material UI library)
- **2021 - Angular 12** - Deprecated support for Internet Explorer 11.
    - includes : Angular 11 : Experimental Webpack 5 support
- **2023 - Angular 16** - SSR, Jest, ESbuild servers
    - includes : Angular 13, 14, 15 : Typed forms, standalone components, Standalone APIs and directive composition API
- **2022 - Angular 22** - Stable Signal forms and Stable accessible components with Angular ARIA.
    - includes : Angular 17, 18, 19, 21 : Updating Standalone (for CLI, Angular directives, components and pipes), NgModule, syntax for control flow and documentation website, Experimental zoneless change detection support, SSR, Experimental Signal forms and Experimental accessible components with Angular ARIA and Zoneless

[historique des versions](https://en.wikipedia.org/wiki/Angular_(web_framework)#Version_history)

## OpenSource code :

- GitHub - [Code source - angular/angular](https://github.com/angular/angular)
- Npm :
    - [Package - Core - @angular/core](https://www.npmjs.com/package/@angular/core)
    - [Package - Tool - @angular/cli](https://www.npmjs.com/package/@angular/cli)

---
_**Partie 2 **_
---

## Prérequis

- NodeJS (inlcude Npm)
- Angular CLI

## Installation de NodeJS & d'Angular CLI

### Installation de NodeJS

[Guide ici](https://nodejs.org/en/download)

### Installation d'Angular CLI

````bash
npm install -g @angular/cli
````

## Création d'un nouveau projet

````bash
ng new first-angular-app --no-zoneless
````

> Par défaut, Angular créer un projet configuré en mode « zoneless » (sans zone) sans l'option `--no-zoneless` _(n'inclus donc pas la librairie zone.js)_.

## VSCode extensions nécessaire

- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
    - of  [Angular](https://marketplace.visualstudio.com/publishers/Angular)
- [Angular Essentials](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials)
    - of [John Papa](https://marketplace.visualstudio.com/publishers/johnpapa)

## Démarrage du projet

````bash
npm start
````

## Eléments principaux à connaitre

- Les essentiels de Angular
- Les Deep Dives : components, directives, pipes, services & DI, change detection, HTTP, forms, routing, ...