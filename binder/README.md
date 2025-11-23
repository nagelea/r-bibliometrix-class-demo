# R + bibliometrix 课堂演示环境（Binder）

这个仓库用于通过 Binder 启动在线 RStudio，并演示使用 **bibliometrix / biblioshiny** 进行文献计量和知识图谱分析。

## 一、通过 Binder 打开 RStudio

点击下面链接（课堂用）：

👉 https://mybinder.org/v2/gh/nagelea/r-bibliometrix-class-demo/HEAD?urlpath=rstudio

> 第一次打开会触发环境构建，如果失败可以稍后刷新重试。

## 二、在 RStudio 中启动 biblioshiny

在 Console 中运行：

```r
library(bibliometrix)
biblioshiny()
