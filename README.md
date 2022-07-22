# book-keeping-fullstack

前后端分离的记账项目，适合移动端使用。

后端：`eggjs`
前端： `React`
数据库： `Mysql`

## Create Project

`$ npm init egg --type=simple --registry=china`

或者 `yarn create egg --type=simple --registry=china`

## QuickStart

<!-- add docs here for user -->

see [egg docs][egg] for more detail.

### Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

```bash
$ yarn install
$ yarn dev
$ open http://localhost:7001/
```

如果`yarn dev`失败，重新安装 egg-bin 即可：`yarn add --dev egg-bin`

### Deploy

```bash
$ npm start
$ npm stop
```

### npm scripts

- Use `npm run lint` to check code style.
- Use `npm test` to run unit test.
- Use `npm run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.

[egg]: https://eggjs.org