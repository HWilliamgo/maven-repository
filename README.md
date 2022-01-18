# Maven-Repository
这是一个HWilliamgo个人的maven仓库，可公开下载。

maven仓库配置：

``` kotlin
// 首选，利用gitee作为仓库
maven("https://gitee.com/HWilliamgo/maven-repository/raw/SNAPSHOT")
// 次选，利用github作为仓库，下载速度较慢
maven("https://github.com/HWilliamgo/maven-repository/raw/SNAPSHOT")
```

# 库列表
| 项目                                                       |
|------------------------------------------------------------|
| [FastViewTree](https://github.com/HWilliamgo/FastViewTree) |


# gitee镜像仓库
利用了开源项目：https://github.com/Yikun/hub-mirror-action

并参考了文章：https://www.cnblogs.com/ssgeek/p/15009012.html

采用github action的自动化持续集成工具，自动地将这个仓库的所有代码同步覆盖到gitee。