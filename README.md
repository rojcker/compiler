凤凰顶真队的编译器

写好以后先在github上加我好友，我给你们权限
然后把仓库先克隆了，在给自己写的东西塞到已创建文件夹的相应位置，在push到上面

# 合作者上传代码指南

请按照以下步骤把代码上传到仓库。

包括：初始化仓库、关联远程仓库、提交代码、推送、拉取、权限、PR等。

# Git + GitHub 合作上传代码全流程教程（从零开始）

本教程帮助你从零开始，把代码上传到远程仓库，参与团队协作开发。

---

## 1. 安装 Git

- Windows: [Git 官网](https://git-scm.com/download/win) 下载并安装  
- Mac: 终端执行 `git --version`，若未安装会提示安装  
- Linux: 终端执行 `sudo apt install git`（Ubuntu/Debian）或 `sudo yum install git`（CentOS）

---

## 2. 配置 Git 用户信息（只需第一次配置）

```bash
git config --global user.name "你的名字"
git config --global user.email "你的邮箱"
````

---

## 3. 新建本地代码仓库（初始化）

如果你已经有项目代码，进入项目根目录，执行：

```bash
cd /path/to/your/project
git init
```

这会创建一个本地 Git 仓库。

---

## 4. 关联远程仓库

请向项目负责人索要远程仓库地址（通常以 `https://github.com/用户名/仓库名.git` 或 `git@github.com:用户名/仓库名.git` 形式）

```bash
git remote add origin 仓库地址
```

---

## 5. 添加文件并提交

```bash
git add .
git commit -m "首次提交，初始化项目"
```

---

## 6. 推送代码到远程仓库

```bash
git push -u origin main
```

> 注意：如果你的默认分支是 `master`，请替换成 `master`。


## 7. 已有远程仓库，克隆代码

如果你是第一次参与项目开发，仓库已经存在，执行：

```bash
git clone 仓库地址
cd 仓库名
```

---

## 8. 拉取最新代码，避免冲突

```bash
git pull origin main
```

---

## 9. 修改代码后提交

```bash
git add .
git commit -m "说明本次修改内容"
```

---

## 10. 推送最新代码

```bash
git push origin main
```

---

## 11. 无推送权限怎么办？

* 访问仓库页面，点击 **Fork** 按钮，复制仓库到你的 GitHub 账号下。
* 克隆你自己的 Fork：

```bash
git clone 你的Fork仓库地址
cd 仓库名
```

* 在你 Fork 的仓库上修改、提交、推送代码。
* 在 GitHub 页面点击 **Compare & pull request** 发起合并请求（PR）。
* 等待项目负责人审核合并。

---

## 12. 常用 Git 命令总结

| 命令                           | 说明           |
| ---------------------------- | ------------ |
| `git init`                   | 初始化本地 Git 仓库 |
| `git clone <地址>`             | 克隆远程仓库       |
| `git remote add origin <地址>` | 关联远程仓库       |
| `git add .`                  | 添加所有修改到暂存区   |
| `git commit -m "说明"`         | 提交代码并写说明     |
| `git pull origin main`       | 拉取远程最新代码     |
| `git push origin main`       | 推送代码到远程仓库    |

---

## 13. 联系方式

如有问题，欢迎随时联系项目负责人。

---

