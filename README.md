# DataSportsAPI · OpenAPI description

The OpenAPI 3.1 description of [DataSportsAPI](https://datasportsapi.com), a
real-time sports data API for 24 sports: every `/v2` endpoint with its
parameters, responses and schemas.

> **Pre-launch.** Accounts and API keys are open at
> [datasportsapi.com](https://datasportsapi.com); calls to the API start at launch.

`openapi.json` here is the same file the site serves at
<https://datasportsapi.com/openapi.json>; it is generated from the docs and
mirrored to this repository when the contract changes.

## Use it to

- import every endpoint into Postman, Insomnia or Bruno;
- generate a client in your language, e.g.
  `npx @openapitools/openapi-generator-cli generate -i openapi.json -g typescript-fetch -o client`;
- browse the contract in any OpenAPI viewer, next to the
  [docs](https://datasportsapi.com/docs/) and the
  [data reference](https://datasportsapi.com/docs/reference/).

Authenticate with `Authorization: Bearer <your key>`.

## Official clients

- TypeScript / JavaScript: [`datasportsapi` on npm](https://www.npmjs.com/package/datasportsapi) ([source](https://github.com/datasportsapi/datasportsapi-js))
- Python: [`datasportsapi` on PyPI](https://pypi.org/project/datasportsapi/) ([source](https://github.com/datasportsapi/datasportsapi-python))

You may use this description to build and test clients for DataSportsAPI.
Questions: [hello@datasportsapi.com](mailto:hello@datasportsapi.com).
© Noventra Software Ltd.
