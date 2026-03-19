# AdonisJS(v7) Slim Starter Kit

This repository provides the smallest possible AdonisJS application with the framework core and the Japa test runner.

It is designed as a clean and minimal starting point for building AdonisJS applications from scratch, without any additional integrations or opinionated tooling.

# Tech Stack

<table>
  <tr>
    <td><strong>Backend</strong></td>
    <td>
      <a href="https://adonisjs.com">AdonisJS 7.x</a> - Full-featured Node.js framework
    </td>
  </tr>
  <tr>
    <td><strong>Testing</strong></td>
    <td>
      <a href="https://japa.dev">Japa</a> - Delightful testing framework with browser testing support
    </td>
  </tr>
  <tr>
    <td><strong>TypeScript</strong></td>
    <td>
      Full TypeScript support with strict mode enabled
    </td>
  </tr>
</table>

# Installation

```bash
npm init adonisjs@latest -- -K="batosai/adonisjs-slim-starter-kit" --skip-migrations
cd adonisjs-app
```

## Start Developing

```bash
# Run the development server with hot reload
node ace serve --hmr

# Run tests
node ace test

# Type check both backend and frontend
npm run typecheck

# Lint your code
npm run lint

# Build for production
npm run build

# Start production server
npm start
```

Your app will be running at `http://localhost:3333`


---

## Learn More

<table>
  <tr>
    <td>
      <a href="https://docs.adonisjs.com"><strong>📖 AdonisJS Docs</strong></a>
      <br>
      <span>Complete guide to AdonisJS</span>
    </td>
  </tr>
</table>

## Contributing

This slim starter kit is maintained by the Jeremy Chaufourier. Found a bug or have a suggestion? [Open an issue](https://github.com/batosai/adonisjs-slim-starter-kit/issues) or submit a pull request!

---

## License

This slim starter kit is open-sourced software licensed under the [MIT license](LICENSE).
