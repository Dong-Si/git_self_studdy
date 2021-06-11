# GIT演示

## GIT是什么

GIT的三个概念：提交commit、仓库repository、分支branch

## 第一次提交

```c
git add -A
git commit -m"提交信息"
```

git commit	提交;提交更新;提交操作;提交到本地版本库

git add	添加文件;记录更新

![](D:\Desktop\git学习\image-20210611151948265.png)

## 查看提交的历史

```p
git log --stat
```

## 维护项目的日常

```c
工作区打回去
git checkout <filename>

提交后撤回：
git reset HEAD^
```

