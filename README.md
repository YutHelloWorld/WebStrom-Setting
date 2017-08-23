# WebStrom-Setting
A JS standard setting of WebStorm

## 起源

干前端也好几年了，开发工具一直使用的是WebStorm（前端） + Eclipse（后端Java服务）。WebStorm虽然吃内存，但毕竟是IDE，功能自然强大！

一个开发团队中，有的人喜欢用4空格缩进，有的人喜欢用2空格，没有对错之分。我们使用规范，只是为了代码风格统一，方便互相review，避免争论。

这里我根据多年的使用习惯，参考JS社区编程规范，导出了webstorm的设置jar包，方便有需要的同学一键导入使用。

## 特性

- 主题 Material Theme
- Code Style 遵循[JavaScript Standard Style](https://standardjs.com/readme-zhcn.html#usage),补充`"object-curly-spacing": [2, "always"]`,`"comma-dangle": "off"`

## 使用

1. 克隆仓库

```bash
$ git clone https://github.com/YutHelloWorld/WebStrom-Setting.git
```

2. 把仓库中的`setting.jar`导入到WebStorm。操作：File -> Import Settings

3. 选中要格式化的代码，使用格式化快捷键Command+option+L(Mac)格式化代码，就能够使得JS代码保持和JS规范一致。

4. 顺带的，推荐你安装插件：Material Theme UI。方法：Prefences -> Plugin -> Browse Repositories -> 搜索 Material Theme UI 并安装。

5. 效果
![ws](https://user-images.githubusercontent.com/20860159/29484307-641b0cea-84ee-11e7-995a-b56797c3d3b6.jpg)
