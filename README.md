# AngularIranPWA

This project uses [Angular CLI](https://github.com/angular/angular-cli) 22.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## GitHub Pages deployment

This repository includes a GitHub Actions workflow that publishes the production build to GitHub Pages.

- In GitHub, set **Settings → Pages → Build and deployment → Source** to **GitHub Actions**
- Ensure GitHub Pages is already enabled for the repository before relying on the workflow; the workflow does not create the Pages site automatically
- Push changes to the `master` branch to trigger a deployment
- The deployed site will be served from `/PWA-starter/`

## Running unit tests

Run `ng test` to execute the unit tests.

## Running lint checks

Run `ng lint` to execute the ESLint-based lint checks.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
