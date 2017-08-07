# [xpath路径查看工具](//xuexb.github.io/xpath/index.html)

[![code style fecs](https://img.shields.io/badge/code%20style-fecs-brightgreen.svg)](https://github.com/ecomfe/fecs)
[![Build Status](https://img.shields.io/travis/xuexb/xpath/master.svg)](https://travis-ci.org/xuexb/xpath)
[![Test Coverage](https://img.shields.io/coveralls/xuexb/xpath/master.svg)](https://coveralls.io/r/xuexb/xpath?branch=master)
[![DevDependencies](https://img.shields.io/david/dev/xuexb/xpath.svg?style=flat)](https://david-dm.org/xuexb/xpath)

## api

### getXpath
```js
/**
 * 获取元素xpath路径
 *
 * @param  {HTMLElement} element 元素
 * @param  {HTMLElement} [context=document.body] 父节点
 *
 * @return {string}
 */
function getXpath(element, context) {}
```


### parseXpath

```js
/**
 * 解析xpath路径为dom元素
 *
 * @param  {string} query   xpath路径
 * @param  {HTMLElement} [context=document.body] 父节点
 *
 * @return {HTMLElement}
 */
function parseXpath(query, context) {}
```