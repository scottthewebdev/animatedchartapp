# animatedchartapp
A compact Angular sample app demonstrating charts built with `@swimlane/ngx-charts`, Tailwind CSS, and server-side rendering support.


## Features
- Example chart types: line, pie, vertical bar, bubble, and numeric card
- Uses `@swimlane/ngx-charts` for responsive SVG charts
- Tailwind + DaisyUI for lightweight styling
- Basic server-side rendering (SSR) entry for production

## Prerequisites
- Node.js (18+ recommended)
- npm (or yarn)
- Angular CLI (optional for global `ng` usage)

## Install
1. Install dependencies:

```bash
npm install
```

## Development
- Run the dev server with live reload:

```bash
npm start
# or
ng serve
```

- Run tests:

```bash
npm test
```

## Build
- Build production bundle:

```bash
npm run build
```

- Build with watch (development):

```bash
npm run watch
```

## Server-side rendering (SSR)
This project includes an SSR server entry. After building the application, run the SSR server:

```bash
# build first
npm run build

# then run the server (example script present in package.json)
npm run serve:ssr:chart-app
```

## Project Structure (key files)
- `src/app/` — main app, routes and app shell
- `src/charts/` — individual chart components (line, pie, bubble, vertical bar, number card)
- `src/chartdata/` — sample chart data files
- `src/layout/` — navigation and side-drawer UI pieces
- `public/` — static public assets

## Demo
A short demo of the charts is included as a lightweight SVG placeholder (replace with a GIF if you prefer):

![Demo chart](public/demo.svg)

## Notes
- The app is designed as a learning/sample project rather than a production-ready charting platform. Customize chart inputs and styles in `src/charts/` and `src/chartdata/`.

## Contributing
PRs and improvements are welcome — open an issue first for larger design changes.

## License
This repository does not include an explicit license. Add a `LICENSE` file if you intend to permit reuse.
# ChartApp

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.2.2.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
