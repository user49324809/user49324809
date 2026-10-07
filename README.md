# Natalia — Full-stack Developer & Technical Writer

I build web applications across frontend and backend, with a current focus on **React, TypeScript, Node.js, Express, PostgreSQL, PHP, and Laravel**.

I also write practical technical articles about web development, backend architecture, authentication, databases, and implementation mistakes found in real projects.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/user49324809/user49324809/main/assets/engineering-snapshot-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/user49324809/user49324809/main/assets/engineering-snapshot-light.svg">
  <img alt="Engineering snapshot: authentication case study verification and current focus" src="https://raw.githubusercontent.com/user49324809/user49324809/main/assets/engineering-snapshot-light.svg">
</picture>

## What I work with

**Frontend**  
React · TypeScript · JavaScript · Vue 3 · HTML5 · CSS3 · SCSS · Material UI

**Backend**  
Node.js · Express · PHP · Laravel · Yii2

**Databases**  
PostgreSQL · MySQL · MongoDB · SQLite

**Tools**  
Git · GitHub · Docker · Vite · npm · REST API · Postman · Figma

## Featured projects

### Bicycle Authentication Case Study

A practical authentication case study based on a bug I found in an older PHP bicycle-store project: registration stored a password hash, while login compared that stored value with the plaintext password from the form.

I rebuilt the flow with **Express, PostgreSQL, PBKDF2-HMAC-SHA256, random per-user salts, `timingSafeEqual`, parameterized SQL, and server-side sessions**.

The project includes database migrations, session-id regeneration after login, generic credential errors, protected routes, logout, and automated HTTP/password/configuration/persistence tests.

**Verification:** 14 automated tests pass in GitHub Actions.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/user49324809/user49324809/main/assets/auth-flow-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/user49324809/user49324809/main/assets/auth-flow-light.svg">
  <img alt="Authentication case study flow: old PHP project, verification bug, Express redesign, 14 of 14 tests passing" src="https://raw.githubusercontent.com/user49324809/user49324809/main/assets/auth-flow-light.svg">
</picture>

[View the case-study Pull Request](https://github.com/user49324809/bicycle/pull/1)

### Yandex Reviews Integration

A full-stack application with registration, authentication, company settings, and an interface for viewing ratings and reviews. A mock provider is used for demonstration data.

**Stack:** Laravel, Vue 3, Inertia, MySQL, Docker

[Source code](https://github.com/user49324809/yandex_integrations)

### Short Links + QR

A URL-shortening and QR-code service that stores links in a database, redirects users, and collects click statistics.

**Stack:** PHP, Yii2, MySQL, Docker

[Source code](https://github.com/user49324809/shortlink)

### Expense Tracker

An expense-tracking application with date filtering, persistent local data, and visual analytics.

**Stack:** React, JavaScript, Chart.js, localStorage

[Live demo](https://user49324809.github.io/tracker/) · [Source code](https://github.com/user49324809/tracker)

### Frontend Portfolio

A personal portfolio site with project highlights, technologies, and contact information.

**Stack:** React, TypeScript, Vite, SCSS

[Live demo](https://frontend-portfolio-virid-sigma.vercel.app/) · [Source code](https://github.com/user49324809/frontend-portfolio)

## Technical Writing & Engineering Notes

I write practical technical material based on implementation work rather than abstract summaries alone.

Current topics include:

- authentication and password verification;
- backend validation and database constraints;
- SQL safety and parameterized queries;
- sessions and application security;
- frontend/backend contracts;
- database design and scalability;
- explaining programming concepts through concrete analogies and project examples.

One current article grew directly from the authentication bug documented in the Bicycle Authentication Case Study above.

## Engineering approach

I try to make projects easy to inspect and reproduce:

- clear separation of responsibilities;
- input validation and predictable error handling;
- database constraints where application-level checks are not enough;
- automated tests for critical flows and regressions;
- environment configuration outside source code;
- readable documentation and reproducible setup steps;
- GitHub Actions for automated verification where appropriate.

## Currently developing

- React application architecture;
- deeper TypeScript usage;
- backend architecture with Node.js and Java;
- unit and integration testing;
- REST API design and documentation;
- production-oriented database and security practices.

## Contact

Open to **Frontend Developer**, **Full-stack Developer**, and technical writing opportunities.

[Portfolio](https://frontend-portfolio-virid-sigma.vercel.app/) · [GitHub](https://github.com/user49324809)
