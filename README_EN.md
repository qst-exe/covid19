# Kagoshima COVID-19 Task Force website

![](https://github.com/codeforkagoshima/covid19/workflows/production%20deploy/badge.svg)

[![Kagoshima COVID-19 Task Force Website](./static/ogp.png)](https://covid19.code4kagoshima.org/)

### [日本語](./README.md) | English

## How to Contribute

All contributions are welcome!
Please check [How to contribute](./.github/CONTRIBUTING_EN.md) for details.

## Code of Conduct

Please check [Code of conduct for developers](./.github/CODE_OF_CONDUCT_EN.md) for details.

## License
This software is released under [the MIT License](./LICENSE.txt).

## For Developers

### How to Set Up Environments

- Required Node.js version: 10.19.0 or higher

**Use yarn**
```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev
```

**Use docker**
```bash
# serve with hot reload at localhost:3000
$ docker-compose up --build
```

### How to resolve `Cannot find module ****` error

**Use yarn**
```bash
$ yarn install
```

**Use docker**
```bash
$ docker-compose run --rm app yarn install
```

### Deployment to Staging & Production Environments

When `master` branch is updated, the production site (https://covid19.code4kagoshima.org/) will be also updated.

When `staging` branch is updated, the staging site (https://staging-covid19.code4kagoshima.org/) will be also updated.

When `development` branch is updated, the development site (https://development-covid19.code4kagoshima.org/) will be also updated.
