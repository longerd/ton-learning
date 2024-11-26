# Ton learning

## Nodejs

```shell
curl -sL https://deb.nodesource.com/setup_22.x -o nodesource_setup.sh

sudo bash nodesource_setup.sh

sudo apt install nodejs

node -v 

npm -v
```

install from source https://github.com/nodejs/node/blob/main/BUILDING.md

## yarn

```shell
npm install --global yarn

yarn -v
```

common commands:

```shell
yarn init

yarn add packagename

yarn upgrade packagename

yarn remove packagename

yarn install

yarn publish

yarn cache list

yarn global
```

## Tact-template

1. `yarn install` install dependencies
2. ref [tact-template/README.md](./tact-template/README.md)
    ```
    yarn test # To test contract
    yarn build # To build contract
    yarn lint # To find code issues in contract
    yarn deploy # To deploy contract
    ```

