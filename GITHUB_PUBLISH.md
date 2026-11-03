# 发布到 GitHub

此目录已经是可公开发布的仓库结构，且不含本次案例中的品牌产品图和用户账号素材。

## 最快发布方式（GitHub CLI）

在此目录执行：

~~~
git init
git add .
git commit -m "feat: add Xiaohongshu long-term value content skill"
gh repo create xhs-longterm-value-content-skill --public --source=. --push
~~~

仓库创建后，打开 Releases → Draft a new release，上传上一级目录中的
`xhs-longterm-value-content-skill.zip`，版本号建议填写 `v1.0.0`。

## 网页上传方式

若没有 GitHub CLI，也可以在 GitHub 网页中新建同名公开仓库，再将本目录全部文件上传。

建议在 Release 中附上 xhs-longterm-value-content-skill.zip，并将 README 中的“你的用户名”替换为实际 GitHub 用户名。
