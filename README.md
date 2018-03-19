# react-unit-test-mocha-demo
An example of unit testing to react components. This uses Karma, Mocha, and Enzyme.

## 介绍
前端react单测框架, karma + mocha + chai + sinon

## Karma Test
```
npm test
```

## 只用 mocha 测试
需要加入 Enzyme 配置
```
mocha ./test/Button.spec.js --compilers js:babel-core/register --require ./test/test_helper.js
```
