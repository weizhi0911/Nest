## 地址
api：3000
WebSocket：3001
redis：6379


## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Tips

暂时不理解
* 文档连接[https://typeorm.biunav.com/zh/#%E5%88%9B%E5%BB%BA%E5%A4%9A%E5%AF%B9%E5%A4%9A%E5%85%B3%E7%B3%BB](https://typeorm.biunav.com/zh/#%E5%88%9B%E5%BB%BA%E5%A4%9A%E5%AF%B9%E5%A4%9A%E5%85%B3%E7%B3%BB)
```js
createQueryBuilder("photo").innerJoinAndSelect("photo.metadata", "metadata").getMany()
```

