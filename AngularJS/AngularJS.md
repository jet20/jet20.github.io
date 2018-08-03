# AngularJS

## 用WebStorm创建AngularJS项目
- angular-seed创建的(https://github.com/angular/angular-seed)


## TODO
- [ ] AngularJS有哪些组件？
- [ ] 如何划分AngularJS模块？
- [x] $scope vs controllerAs
- [ ] {{}} vs ng-bind & ng-cloak


## AngularJS的基本概念
- module(模块)和app(应用)
	- angular.module
	- ng-app
- controller控制器: ng-controller


## AngularJS模块的概念
```javascript
angular.module('app', []); // 定义模块
angular.module('app'); // 引用模块
```
- 容器： 可以包含自己的控制器、服务、工厂类和指令
- 可以依赖其他模块
- 启动应用


## 控制器职责
- 从服务器获取所需数据
- 决定显示哪些数据
- 用户交互

