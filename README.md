# ng-playground-test-2026

An Angular playground and experiments workspace — a scratch repo for trying out Angular features, components, services, and concepts without polluting production projects.

> **Status:** Fresh workspace. No experiments committed yet — this repo is the starting point for hands-on Angular exploration.

## Purpose

- Experiment with Angular 17/18+ features (standalone components, signals, control flow)
- Prototype reusable UI components and directives
- Try out routing, forms, HTTP, and RxJS patterns in isolation
- Keep learning notes and mini-demos in one place

## Planned Experiments

- Standalone components + `bootstrapApplication`
- Angular signals and computed values
- New template control flow (`@if`, `@for`, `@switch`)
- Reactive forms vs template-driven forms
- Lazy-loaded feature routes
- RxJS operators and state patterns with services

## Getting Started (once experiments begin)

```bash
# requires Node 18+ and the Angular CLI
npm install -g @angular/cli

# the playground will use a standard Angular CLI workspace layout:
# src/app — experiments and demos
# src/assets — static assets

npm install
ng serve        # dev server at http://localhost:4200
ng build        # production build to dist/
```

## Suggested Workspace Layout

```
src/
  app/
    experiments/      # one folder per experiment
    shared/           # reusable components, directives, pipes
    app.component.ts  # root component
angular.json          # workspace config
package.json          # dependencies
```

## Conventions

- Each experiment lives in its own folder under `src/app/experiments/`
- Working experiments get a short demo note in this README
- Keep experiments independent — no cross-experiment imports

## Tech Stack

- **Framework:** Angular (latest)
- **Language:** TypeScript
- **Styling:** SCSS / Tailwind CSS
- **Build:** Angular CLI

---

Built by Girish Lade — [ladestack.in](https://ladestack.in)
