# DataSportsAPI · OpenAPI description

The OpenAPI 3.1 description of [DataSportsAPI](https://datasportsapi.com), a
real-time sports data API for 25 sports: every `/v2` endpoint with its
parameters, responses and schemas.

> **Live.** The API answers today: get a free key (1,000 requests a day, no card)
> at [datasportsapi.com/signup](https://datasportsapi.com/signup/).

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
Questions: [hello@datasportsapi.com](mailto:hello@datasportsapi.com) or the [developer Discord](https://datasportsapi.com/discord).
© Noventra Software Ltd.
