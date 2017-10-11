# Angular Cli with ASP .Net
This project can be used for development of ASP .Net Project with Angular CLI

## Development

Naviage to `ng-app` folder and run `ng serve` in terminal for a dev server. `ng-app` is the angular cli project present in .net project. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build --env=prod --output-hashing none` or `npm run build-prod`to build the project. The build artifacts will be stored in the `Scripts` directory. `Index.cshtml` is already configured to host the build files provided from the angular cli. Now we can host the ASP.Net Application on IIS server

## base tag

update the `<base>` tag present in `Index.cshtml` as per the domain name for prduction deployment in IIS.

