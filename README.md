# 深海的呼唤计划

这是一个中文个人博客：记录生活、旅行、照片与思考。采用 Jekyll + GitHub Pages，并配置 Pages CMS 文章管理。

## 网站地址

https://sabrinagu822.github.io/guxiaomei02.github.io/

## 发布设置

仓库 Settings → Pages → Build and deployment：
- Source：Deploy from a branch
- Branch：main
- Folder：/(root)
- 点击 Save，等待首次构建完成。

## 使用 Pages CMS 管理文章

1. 打开 https://app.pagescms.org/ 并使用 GitHub 登录、授权。
2. 选择仓库 `SabrinaGu822/guxiaomei02.github.io` 和 `main` 分支。
3. 进入「文章」集合新增文章，填写标题、日期、slug、分类、标签、摘要、封面和正文。
4. 图片可上传至 `assets/images`。提交后 GitHub Pages 会自动重新构建。

## 站点栏目

日记与随笔、旅行、照片、学习笔记、读书与观影、生活碎片。

## 本地预览

安装 Ruby 后运行：
```sh
bundle install
bundle exec jekyll serve
```

## 注意

仓库为公开仓库，提交的文章、图片和源码都可被公开访问。请勿上传密码、访问令牌或不希望公开的私人内容。
