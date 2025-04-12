# CoachFe

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


1.Create a new branch.
2.Merge all created branches to development. 
3.After merege delete this branch.

For Code upload on Dev server

1.Git checkout developomentand run commond  git branch to verify branch.
3.Git pull from developomentand
4.ng build --configuration dev
5. after build go to dist file exclude assets folder and create zip rest all files.
6. after upload dist file extraxt this file move to root file.

For Code upload on Stage server
1.Create a new branch  stagerelease<date> from development branch
2.Git checkout stagerelease<date> and run common git branch to verify branch.
3.Git pull from stagerelease<date>
4.ng build --configuration staging
5.After build go to dist file exclude assets folder and create zip rest all files.
6.After upload dist file extraxt this file move to root file.
7.after freez stage create a MR from stagerelease<date> to stage and merge MR.
8.Git pull from stage
9.ng build --configuration staging
10.After build go to dist file exclude assets folder and create zip rest all files.
11.After upload dist file extraxt this file move to root file.

For Code upload on Prod server
1.Create a Mr stage from production branch
2.create New branch productionbackup<date> form production branch
2.Git checkout production and run common git branch to verify branch.
3.Git pull from production
4.ng build --configuration live
5.After build go to dist file exclude assets folder and create zip rest all files.
6.After upload dist file extraxt this file move to root file.

