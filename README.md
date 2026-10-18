# 梳忆·老巷木梳坊

苏州木梳非遗主题的单页互动游戏原型，使用原生 HTML、CSS 和 JavaScript，无需安装依赖。

## 项目结构

```
.
├── index.html
├── assets/
│   ├── home.png   # 首页背景图（需上传）
│   └── level.png  # 关卡背景图（需上传）
└── .github/
    └── workflows/
        └── pages.yml
```

## 添加背景图片

把首页图命名为 `home.png`，把工坊关卡图命名为 `level.png`，上传到仓库的 `assets/` 文件夹。当前页面已经引用这两个相对路径。

## 本地预览

直接用 Chrome 或 Edge 打开 `index.html` 即可体验。无需构建步骤。

## GitHub Pages

仓库已包含 GitHub Actions 工作流：推送到 `main` 后会尝试部署仓库根目录。首次使用还需要在 GitHub 仓库 Settings → Pages 中将 Build and deployment 来源设置为 **GitHub Actions**。若工作流因 Pages 尚未启用而失败，请先完成此设置，再到 Actions 页面重新运行。

## 玩法

- 开启记忆并进入木梳坊
- 查看苏式木梳工艺介绍
- 点击选木、开齿、打磨上蜡等知识卡片
- 点击祥云、牡丹、卷草、如意纹样查看寓意
- 完成祖母梳头与童年工坊两段回忆
- 阅读陈师傅的结语

## 说明

这是可继续扩展的前端原型。传统工艺知识、非遗表述与图片素材授权请在正式比赛提交前核实。
