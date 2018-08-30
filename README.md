# Webpack4-Karma-Mocha-Chai-Demo

## 1.项目说明
基于`webpack`4.0版本的自动化测试套件配置示例（2018年8月全新，亲测有效）
代码覆盖率报告：
      
单元测试结果：

## 2.相关框架及插件说明
- `webpack`  项目打包
- `babel`  ES2015+语法转换
- `karma`  支持在不同浏览器中运行的测试驱动框架
- `karma-chrome-launcher` karma-**-launcher均为对应浏览器的加载插件
- `karma-coverage-instanbul-reporter` 覆盖率报告生成插件
- `karma-mocha-reporter` 单元测试报告生成插件
- `mocha`  单元测试框架
- `chai`  支持*assert*,*expect*,*should*不同语法风格的断言库
- `istanbul` js编写代码覆盖率检测工具
- `istanbul-instrumenter-loader` 业务逻辑代码loader（用于区分测试代码）

## 3.相关文档
- `Karma`官网已废，新版需要从`github`进
    - [https://karma-runner.github.io/2.0/index.html](https://karma-runner.github.io/2.0/index.html)

- `webpack`4.0如何集成`karma`
[https://www.webpackjs.com/guides/integrations/](https://www.webpackjs.com/guides/integrations/)

- 使用`istanbul-instrumenter-loader`处理业务逻辑代码
[https://www.webpackjs.com/loaders/istanbul-instrumenter-loader/](https://www.webpackjs.com/loaders/istanbul-instrumenter-loader/)

- 使用`karma-coverage-istanbul-reporter`生成代码覆盖率报告
[https://github.com/mattlewis92/karma-coverage-istanbul-reporter](https://github.com/mattlewis92/karma-coverage-istanbul-reporter)

## 4.鸣谢
本篇中业务逻辑部分代码来自[karma-webpack-example](https://github.com/gabel/karma-webpack-example)项目（该项目中配置仍然有效，使用的是`webpack`低版本API）。
