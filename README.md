# Personal Site

这是一个用于学习 Git、GitHub 和 VSCode 的个人介绍网页项目。

项目地址：

- GitHub: <https://github.com/lizhanran2008/personal-site>

## 项目内容

- `index.html`：网页结构
- `style.css`：网页样式

## 学习目标

- 学会创建本地项目
- 学会使用 Git 提交版本
- 学会把项目上传到 GitHub

## Git 最基础流程

第一次创建项目时：

```bash
git init
git add .
git commit -m "Create personal site"
```

把项目上传到 GitHub：

```bash
git branch -M main
git remote add origin https://github.com/lizhanran2008/personal-site.git
git push -u origin main
```

以后每次更新项目时：

```bash
git status
git add .
git commit -m "Update personal site"
git push
```

## 下一步可以改什么

- 把网页标题改成你的名字
- 加上你的兴趣、学校或学习方向
- 放一个头像
- 以后继续增加新项目链接
