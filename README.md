# Screeps Starter

Local development environment for [Screeps game](https://screeps.com).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
You will need [Node](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com/lang/en/) installed on your system.

### Setup

Install all dependencies.

```
yarn install
```

Rename `screeps.sample.json` file to `screeps.json` and fill it with your credentials.

```
{
    "email": "email@dot.com",
    "password": "password",
    "protocol": "https",
    "hostname": "screeps.com",
    "port": 443,
    "path": "/",
    "branch": "auto"
}
```

Run development server.

```
yarn start:sim or yarn start:pserver
```

### Stack

- Typescript
- Prettier
- ESLint
- Rollup

## Deployment

When you are using `yarn start:[env]` the code is automatically building and deploying to Screeps server configured in `screeps.json` file.

## Contributing

Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments

- All Screeps related assets (logos, screenshots) are owned by [Screeps Game](https://screeps.com).
