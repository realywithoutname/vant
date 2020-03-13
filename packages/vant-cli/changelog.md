# 更新日志

### [v2.2.5]

`2020-03-08`

- 升级依赖
- 优化代码块与底部文字之间的间距
- 修复 create-vant-cli-app 初始化时报错的问题

### [v2.2.4]

`2020-02-14`

- 修复在 windows 上构建出的样式入口文件路径错误的问题 ([#5655](https://github.com/youzan/vant/pull/5655)

### [v2.2.3]

`2020-02-13`

- 链接颜色调整为蓝色

### [v2.2.2]

`2020-02-05`

- 修复在 windows 上获取 markdown 路径错误的问题 ([#5626](https://github.com/youzan/vant/pull/5626))

### [v2.2.1]

`2020-02-04`

- 升级 babel@7.8
- 修复切换版本时跳转 undefined 的问题 ([#5620](https://github.com/youzan/vant/pull/5620))

### [v2.2.0]

`2020-01-19`

- 升级 @vant/eslint-config@2.0.0

### [v2.1.8]

`2020-01-18`

- 新增 create-vant-cli-app 初始化命令
- 新增 --version 选项
- 优化站点导航栏颜色
- 优化站点代码块颜色

### [v2.1.7]

`2020-01-15`

- 优化 help 命令 
- 优化控制台输出信息

### [v2.1.6]

`2020-01-12`

- 支持自定义 Postcss 配置
- 支持自定义 devServer 端口
- 优化文档站点的 meta 字段
- 新增 API 文档中的版本标签样式

### [v2.1.5]

`2020-01-10`

- 修复编译时未替换 import 语句中的 CSS 后缀的问题
- 升级 husky 版本到 4.0

### [v2.1.4]

`2020-01-06`

**Bug Fixes**

- 锁死 @vue/test-utils 版本为 1.0.0-beta.29

### [v2.1.3]

`2020-01-06`

**Feature**

- 增加 cache-loader，提高构建速度
- 调整 jest setup 文件执行时机，延迟至 env 初始化后执行

### [v2.1.2]

`2020-01-05`

**Feature**

- 优化文档站点样式，统一圆角大小

**Bug Fixes**

- 修复 windows 下路径分隔符错误的问题
