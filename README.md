# Irobot-algorithm's Blog

## 1. 提交流程概要

1. fork 本仓库
2. 将 **符合命名和头部信息的规范的md文件**(例如`2023-12-15-single-step.md`) 提交到fork仓库的_posts目录下
3. 提pr, 审核通过后自动编译成功后即可

## 2. 博客规范

### 2.1 markdown文件命名

markdown文件采用 `<year>-<month>-<date>-<name-of-Blog>` 的方式命名，放置于 `_posts/` 目录下，其中 `<name-of-Blog>` **不允许有空格，用 `-` 代替**。请尽量简洁并符合英文语法。此名称中的 `<year>-<month>-<date>` 仅用于区别不同的博客，方便识别，**分别用 4 、 2 、 2 个数字表示**，如 `2000-01-01` 。

### 2.2 markdown头部规范

每篇博客开始都需要配置 config 选项，**必须放置于博客最开始，采用 yaml 语法**。一个通用的头部如下，创建博客可以复制以下代码使用：

```yaml
---
title: 通信教程
date: 2023-12-15
author: eren  # 作者信息，使用前需要在_data/authors.yml下新增你的信息。如果有多人作者，请去掉掉这一行。
categories: [Edu] # 分类，规范看下文
tags: [通信]   # 标签，规范看下文
pin: false		# 是否置顶，请设为 false ，仅我可以选择置顶与否
math: false		# 是否使用 mathjax 公示，不使用请关闭，加速网页加载
mermaid: false		# 是否使用 mermaid 绘图（https://github.com/mermaid-js/mermaid），不使用请关闭，加速网页加载
---
```


### 2.3 图片和其他小附件

每篇博客 `<name-of-blog>.md` 所使用的图片和其他附件放置于 `assets/imgs` 目录下的同名目录 `<name-of-blog>` 下。这样规定的原因是为了便于管理和更新。

最终提交的图片的路径**不是本地的相对路径**，而是 GitHub的RAW上的路径。在最后上传时，应将博客中**所有的图片路径**改为` https://raw.githubusercontent.com/IRobot-Algorithm/irobot-algorithm.github.io/main/`+ `assets/imgs/<name-of-blog>/xx.img` 
> 例如你的**相对路径**是`assets/imgs/2023-12-15-comunitcation/candump`,那么最后提交时应该改成`https://raw.githubusercontent.com/IRobot-Algorithm/irobot-algorithm.github.io/main/assets/imgs/2023-12-15-comunitcation/candump`）


### 2.4 分类规范

` TODO `

### 2.5 标签规范

` TODO `

## Acknowledge

网站使用了[chirpy-starter](https://github.com/cotes2020/chirpy-starter)的模板, 规范部分参考了[Harry-hhj](https://github.com/Harry-hhj/Harry-hhj.github.io/tree/master)的规范
