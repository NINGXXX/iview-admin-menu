git clone 的是2019年3月26日最新的master代码
在master分支做了动态路由的修改，后台菜单为mock数据，修改为真正的请求，使用者必回知识，不做解释


## Getting started
```bush
# clone the project
git clone `项目地址`

// install dependencies
npm install
不能用
yran install
装yran（自行百度）

// develop
npm run dev
```

## Build
```bush
npm run build
```

项目运行起来吧，是不是刷新一下或者点击下，出现了重复菜单呢？
原因就是在`src/router/index.js`  我标注的那句代码，需要根据实际场景放置，不能随意放的。
好了，少年，自己想想吧，那句代码的最终归宿在哪里
## License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-present, iView
