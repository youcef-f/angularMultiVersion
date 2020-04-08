# angular Multi Version

##  Installation specifique d'une  Version d'angular pour un projet données

## Version Global 6.1
La version global installé est la version **6.1.3** d'angular-ci

## Angular 4
Nous souhaitons travailler sur la version d'angular 4. Il faut installer la version de l'outil angular Cli **1.1**


## Installation

### Creaton d'un repertoire vide
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS
````bash
mkdir angularJSProjet
````


### Initialisation le projet
Se position au sein de ce repertoire puis lancer la commande npm init

````bash
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS
cd angularJSProjet

C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet
npm init
````

### Installer la version d'angular CLI désiré.

````bash
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet
λ npm install @angular/cli@1.1
````

## Suppression des repertoires et fichiers generés localement excepté le repertoire **node_modules**

````bash
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet
λ dir
 Le volume dans le lecteur C s’appelle OS
 Le numéro de série du volume est 2E66-D7B4

 Répertoire de C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet

08/04/2020  14:22    <DIR>          .
08/04/2020  14:22    <DIR>          ..
08/04/2020  14:22    <DIR>          node_modules
08/04/2020  14:22           292 980 package-lock.json
               1 fichier(s)          292 980 octets
               3 Rép(s)  29 933 797 376 octets libres
````


````bash
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet
λ rm package-lock.json
````

## Creation d'un nouveau projet angular sur la base d'angular cli désiré
````bash
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet
λ ng new GestionComptesAngular4
Your global Angular CLI version (6.1.3) is greater than your local
version (1.1.3). The local Angular CLI version is used.

To disable this warning use "ng config -g cli.warnings.versionMismatch false".
installing ng
  create .editorconfig
  create README.md
  create src\app\app.component.css
  create src\app\app.component.html
  create src\app\app.component.spec.ts
  create src\app\app.component.ts
  create src\app\app.module.ts
  create src\assets\.gitkeep
  create src\environments\environment.prod.ts
  create src\environments\environment.ts
  create src\favicon.ico
  create src\index.html
  create src\main.ts
  create src\polyfills.ts
  create src\styles.css
  create src\test.ts
  create src\tsconfig.app.json
  create src\tsconfig.spec.json
  create src\typings.d.ts
  create .angular-cli.json
  create e2e\app.e2e-spec.ts
  create e2e\app.po.ts
  create e2e\tsconfig.e2e.json
  create .gitignore
  create karma.conf.js
  create package.json
  create protractor.conf.js
  create tsconfig.json
  create tslint.json
Successfully initialized git.
Installing packages for tooling via npm.
Installed packages for tooling via npm.
You can `ng set --global packageManager=yarn`.
Project 'GestionComptesAngular4' successfully created.
````



Le repertoire **node_modules** à la racine du repertoire n'est plus nécessaire. Attention de ne pas supprimer celui à l'intérieur du nouveau projet **GestionComptesAngular4**.
````bash
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet
λ dir
 Le volume dans le lecteur C s’appelle OS
 Le numéro de série du volume est 2E66-D7B4

 Répertoire de C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet

08/04/2020  14:23    <DIR>          .
08/04/2020  14:23    <DIR>          ..
08/04/2020  14:23    <DIR>          GestionComptesAngular4
08/04/2020  14:22    <DIR>          node_modules  <<--- supprimer
               0 fichier(s)                0 octets
               4 Rép(s)  29 414 424 576 octets libres
````


````bash
C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet
λ cd GestionComptesAngular4

C:\PERSONNEL\eclipse-workspace-java-training\GestionComptesSpringBootJPAHibernateRestfulSOAPRMIAngularJS\angularJSProjet\GestionComptesAngular4 (master -> origin)
λ ng version
Your global Angular CLI version (6.1.3) is greater than your local
version (1.1.3). The local Angular CLI version is used.

To disable this warning use "ng config -g cli.warnings.versionMismatch false".
    _                      _                 ____ _     ___
   / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
  / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
 / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
/_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
               |___/
@angular/cli: 1.1.3
node: 10.5.0
os: win32 x64
@angular/animations: 4.4.7
@angular/common: 4.4.7
@angular/compiler: 4.4.7
@angular/core: 4.4.7
@angular/forms: 4.4.7
@angular/http: 4.4.7
@angular/platform-browser: 4.4.7
@angular/platform-browser-dynamic: 4.4.7
@angular/router: 4.4.7
@angular/cli: 1.1.3
@angular/compiler-cli: 4.4.7
@angular/language-service: 4.4.7
````

## le repertoire peut etre deplacer partout ensuite.


###correspondance entre angular-Cli et Angular

|Angular-CLI version        | Angular version             |
|--------------              | ---------                  |
| angular-cli@0.1.0          | Angular 2                  |
| @angular/cli@1.1.0         | Angular 4.0.0              |
| @angular/cli@1.4.10        | Angular 4.2.4              |
| @angular/cli@1.5.0         | Angular 4.4                |
| @angular/cli@1.7.4         | Angular 5.2.0              |
| @angular/cli@6.2.8         | Angular 6.1.0              |
| @angular/cli@7.3.9         | Angular 7.2.0              |




