# Serverless Lambda Layer Example

It is an example to demonstrate how to create lambda layer with serverless framework. It includes the sharp layer, which target at node version 10.15.0 and a layer includes various useful node modules. After understanding the usage of lambda layer, you can have a look on this [repository](https://github.com/kenyipp/serverless-realtime-image-resizer) to see how to integrate lambda layer in both local development and production environment.

## Installation

```sh
$ cd ./utils 
$ npm run install:sharp
$ cd ../utils
$ npm run install
$ cd ..
$ serverless deploy
```

## Remark
You should have a look on this [repository](https://github.com/mthenw/awesome-layers) before creating your own lambda layer.

