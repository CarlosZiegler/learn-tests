# LEARN-TESTS Monorepo

This monorepo is a dynamic testing ground for developing applications with various frameworks and improving testing techniques. By leveraging Turborepo, we maintain high-performance builds and ensure consistent tooling across all applications.


## Apps

- `hono-app`: A Hono framework-based application for building fast and scalable server-side applications.
- `nest-app`: An application built with NestJS, a progressive Node.js framework for building efficient and reliable server-side applications.
- `nextjs-app`: A React-based framework for rendering on the server side, perfect for building SEO-friendly and performant web applications.
- `remix-app`: A full stack web framework that allows for smoother and simpler development of modern web applications.
- `vite-app`: A lightning-fast frontend build tool that provides a smooth and efficient developer experience.

## Tools

- `biome.js`: Format, lint, and more in a fraction of a second.
- `TypeScript`: A strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.
- `PNPM`: An efficient and fast package manager for Node.js that saves disk space and boosts performance by symlinking packages.
- `Turborepo`: A high-performance build system for JavaScript and TypeScript codebases that enables efficient and consistent builds across applications.

## Test Frameworks
- `JEST`
A delightful JavaScript Testing Framework with a focus on simplicity. It works with projects using Babel, TypeScript, Node.js, React, Angular, Vue, and more. Jest is often used for unit and integration testing.

- `VITEST`
A Vite-native test framework. It's fast, featuring native ES Modules support. Vitest is optimized for Vite and offers a similar developer experience to Jest.

- `React Testing Library`
A lightweight solution for testing React components. It provides utility functions to interact with React components similar to how users would. It encourages better testing practices by focusing on behavior rather than implementation.

- `MSW` (Mock Service Worker)
An API mocking library that uses Service Worker API to intercept actual requests. MSW is great for mocking REST/GraphQL APIs and helps in creating reliable and consistent tests by removing external dependencies.

- `Playwright`
A framework for end-to-end testing of web applications. It allows testing across all modern rendering engines (Chromium, Firefox, and WebKit). Playwright is capable of running tests in headless mode and can be used for browser automation.

- `Cypress`
An all-in-one testing framework focused on end-to-end testing, though it can handle unit and integration tests too. Cypress runs in the same run-loop as the application, making asynchronous testing simpler and more robust.

## Usage

To get started with this monorepo, run the following command:

```bash
pnpm install
```
This will install dependencies for all packages and apps within the monorepo, leveraging PNPM's workspace functionality for efficiency.

## Contributing
Contributions are welcome! Please read our contributing guidelines for how to get started.

For detailed information about each package and app, navigate to their respective directories and read the specific README.md files.

## License
This project is open-sourced under the MIT license.