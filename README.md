# 团队介绍

我们是一支来自不同地方的孩子，共同朝着前端的方向努力。
之所以队名叫 Prism（棱镜）是因为希望我们能折射出色彩斑斓的作品。

## 团队成员介绍

### kyon

- 2014.03 毕业，研究生期间主要工作是图像相关，做过增强现实相关 Android 应用，在豆瓣阅读实习期间获益良多。对页面布局以及用户交互等事颇有兴趣和耐心，故而转做前端，欢迎大家访问我的 [网站](http://kyons.me)
- 信息爆炸时代下苟且偷生，一边焦虑总是有学不完的知识，一边散漫的拖延时间
- 喜欢看小说、漫画、美剧、拼装东西，爬山或许是新晋的爱好
- 近期的目标是找到一份满意的前端工作，中长期目标是叱诧前端，终极目标是财务自由 XD


### paopaomale

正在慕课网学习前端基础，正在看js和jQuery。虽然基础不是很好,但是会坚持学好前端。

目前找了一个前端的工作，希望自己一年后会能成为一个超级棒的前端。

### linkmyth

-  热爱编程，坚信编程中蕴含着人生的小智慧
-  最爱C语言，对C语言实现各种算法的过程如痴如醉
-  立志成为一名优秀的黑客，从一名前端小白做起

### anisweir

我就读于中国计量学院信息工程学院计算机科学与技术专业。
爱好网站前端。


### GeekPlux

一个普通的程序猿，代码爱好者。好奇心比别人强一点、兴趣稍微广泛一些，其他还需要多学习。
喜欢质疑一切，不喜欢给自己贴标签，爱好金庸武侠和各类音乐。希望自己最终能成为一名：

- 知行合一的理想主义者
- 温和坚定的自由主义者
- 骄傲谦逊的理性主义者

我的博客：[GeekPlux's blog](http://www.geekplux.com/)

----------

## introduction

> 这份 README 可以大家一起来编辑

### 任务

开发一个网站介绍我们的队伍和成员


### Git 入门参考

- [Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

### 协作模式（步骤）

按照以下的步骤，可以永远保证我们的 `master` 分支是稳定版，`develop` 分支是最新版。

- 先 Clone 这个 repo 到本地
- 用下面的命令新建并关联远程远程的 `develop` 分支

```shell
git branch --track develop origin/develop
```

- 每次自己开发时先在 `develop` 分支下

```shell
git pull origin develop
```

- 再用下面的命令创建一个新分支 `patch`

```shell
git checkout -b patch
```

- 在 `patch` 分支上开发
- 开发完毕后，切回 `develop` 分支

```shell
git checkout develop
```

- 同样是先运行 `git pull`（永远让 develop 分支保持最新）

```shell
git pull origin develop
```

- 然后 merge 你刚才开发完的分支 patch

```shell
git merge patch
```

- 这时可能会有冲突（conflict），处理完冲突后，再用 `git push`，将代码 push 到远程

```shell
git push origin develop
```

这个以上的步骤虽然繁琐，但是多操作几次之后就熟练了。
等我们确定 `develop` 分支上的代码没有问题，是一个稳定版本后，再将其 merge 到 `master` 分支上。

```shell
git checkout master
git pull origin master
git merge develop
git push origin master
```


### deadline

7月17日
