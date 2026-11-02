# My Repo

第一个通过本地 Git 推送到 GitHub 的测试项目。

## 内容

- `index.html` —— 一个静态页面，双击即可在浏览器打开
- `README.md` —— 本说明文件
- `.gitignore` —— 忽略系统与编辑器产生的临时文件

## 本地运行

直接用浏览器打开 `index.html`，或者在本目录执行：

```bash
python -m http.server 8000
```

然后访问 http://localhost:8000

## 日常流程

```bash
git status                  # 看改了什么
git add .                   # 暂存所有改动
git commit -m "说明"         # 提交到本地
git push                    # 推送到 GitHub
```
