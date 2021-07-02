11111111
22222222
## 创建本地仓库

- 创建.gitignore文件, 并配置忽略
- git init  初始化工作区
- git add .  添加到暂存区
- git commit -m "init app"  提交版本区



## 创建远程仓库

- 指定仓库名称
- 指定为公开的



## 将本地仓库的代码推送到远程仓库

- git remote add origin https://gitee.com/zxfjd3g/code-210422.git : 记录远程仓库
- git push -u origin master: 将master分支推送到远程
- 创建dev分支并推送到远程
  - git checkout -b dev
  - git push origin dev



## 入职第一天

- clone远程仓库到本地:

  ```
  git clone 仓库clone地址
  ```

- 根据远程dev, 创建本地dev

  ```
  git checkout -b dev origin/dev
  ```

- 根据本地dev, 创建个人分支

  ```
  git checkout -b xfzhang
  ```

- 编码实现功能, 并提交

  ```
  
  ```

  