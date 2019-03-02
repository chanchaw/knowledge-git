# git 使用步骤

### 安装

### 第一次使用

* git 用户设置：

  ```js
  git config --global user.name "用户名可中文"
  git config --global user.email "EMAIL地址"
  ```

### 创建 git 仓库

* 初始化 git 仓库

  ```js
  git init
  ```

* 注册远端仓库

  ```js
  git remote add 缩略名称 远端仓库地址
  ```

* 从远端克隆项目：

  ```js
  git clone 远端地址
  ```

### 提交更新

* 提交更新的步骤是：先添加再提交：

  ```js
  git add . //添加本地仓库下的所有文件到暂存区
  git add 文件名称 //添加单个文件
  ```

* 提交更新：

  ```js
  git commit -m "更新说明，一定要填写"
  ```

  