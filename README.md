# 2PG Dashboard
Dashboard to customize 2PG; made with TypeScript + Angular 9 -> https://2pg.xyz
[![Run on Repl.it](https://repl.it/badge/github/theADAMJR/2PG-Dashboard)](https://repl.it/github/theADAMJR/2PG-Dashboard)

**Used by**: [2PG](https://2pg.xyz), [3PG](https://3pg.xyz), [6PG](https://github.com/theADAMJR/6PG), [DBots](https://dbots.co)

![Guild Dashboard](https://i.ibb.co/n3D80Dx/2-PG-Dashboard.png)
![Audit Log](https://2pg.xyz/assets/docs/img/dashboard-v0.2.0b.png)

## Prerequisites
- Know how to use JavaScript, TypeScript, and Angular 9

## Discord Bot Setup
Make sure you have redirects set to the /auth link you will be using.
This will be used in the final step of the OAuth2 login.
  
![Redirects](https://i.ibb.co/9pbfVwL/updated-redirects.png)

If you change your redirects, **regen your application secret**.

---

## Further Notes
- **Channels and roles are publically available through the API**
  - Used to provide more user-friendly select options
  - This is to also to avoid rate limiting
- **Everything within the /src folder is public**
  - Keep the API, Server, and bot isolated to avoid extra bundle size, or your bot tokens being bundled on the client side (not good)
  - Just avoid associating any tokens or secrets with the webapp itself
  - This also applies to the bot
- **If renaming config files, make sure to .gitignore them**
 - This is done by default, but I've made this mistake many times

---

# Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
