# Frontend

## Requirements
- [Node.js](https://nodejs.org) version 14
- [yarn](https://yarnpkg.com) version 1

Additionally, an Instagram access token is required. [Follow this guide](https://developers.facebook.com/docs/instagram-basic-display-api/getting-started) to retrieve it and store the token in the `.env` file in the `frontend` directory.

## Setup

Install netlify cli for functions exection:
```bash
yarn global add netlify-cli
```

Execute all commands from a terminal navigated to this directory.

Install dependencies:
```bash
yarn
```

## Development

Start development environment:
```bash
ntl dev
```

## Testing

Start tests (make sure the app is running and serving):
```bash
yarn test
```

Running Cypress Testrunner is currently only possible on the host. So there is no way with docker-compose at this time.

```bash
yarn test:ui
```
