## Git 工作区域

**Git Repository (Git 仓库)** 最终确定的文件保存到仓库，成为一个新的版本，并且对他人可见

**暂存区** 暂存已经修改的文件最后统一提交到 git 仓库

**工作区 (Working Directory)** 添加、编辑、修改文件等操作

## 向仓库中添加文件流程

工作区 -> 暂存区 -> Git Repository

git status

git add [file]

git status

git commit -m "description描述"

git status

## Git 基础设置

1. 设置用户名

   ```bash
   git config --global user.name 'name'
   ```

2. 设置用户名邮箱

   ```shell
   git config --global user.email 'name@email'
   ```

3. 查看设置

   ```shell
   git config --list
   ```

   **--global** 	 # 全局初始化

## 初始化一个新的 Git 仓库

1. 创建文件夹

2. 在文件内初始化 git (创建 git 仓库)

   ```shell
   git init	# 将在当前目录生成 .git 隐藏文件
   ```

## 向仓库添加文件

## Git 克隆

```shell
git clone 仓库地址
```

## Git 提交远程仓库

```shell
git push
```

