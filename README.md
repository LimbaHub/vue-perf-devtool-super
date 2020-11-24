# vue-perf-devtool-super
Develop base on https://github.com/vue-perf-devtool/vue-perf-devtool

用来分析Vue应用程序性能的Chrome插件。原版已停止维护。
在原版的基础上修复了一些bug，并增加了排序功能。

### 使用
- 下载本仓库内容到本地
- 将整个文件夹拖动到chrome扩展程序面板
- 在```node_modules/vue/dist/vue.runtime.ems.js```中找到``` perf.clearMeasures(name) ```，把注释取消掉
- 加载页面，或触发vue组件更新后，应能看到如下效果：
![avatar](https://raw.githubusercontent.com/LimbaHub/vue-perf-devtool-super/main/vue-perf-devtool-super.png)
