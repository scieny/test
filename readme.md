# github 使用教程

### 1. 在github上创建一个仓库
`https://github.com/scieny/test.git`

### 2. 在本地创建一个文件夹，初始化为git仓库
`git init`

### 3. 新建一个文件readme.md

### 4. 将工作区文件添加到版本库缓存区
`git add readme.md`

如果要添加当前目录下的所有文件，用 `git add .`

### 5. 将缓存区文件提价到版本库
`git commit -m "提交的消息"`

### 6. 添加远程仓库，也就是github上的仓库地址
`git remote add origin https://github.com/scieny/test.git`

### 7. 将本地仓库推送到远程仓库