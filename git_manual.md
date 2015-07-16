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
