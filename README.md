# 马来西亚入境旅游数据可视化

马来西亚2024年入境旅游数据交互式可视化面板。

## 运行要求

- Python 3.x（无需安装额外的Python库）

## 依赖说明

本项目使用Python内置的http.server模块，无需通过pip安装任何依赖包。所有可视化库（Vega、Vega-Lite、Vega-Embed）通过CDN在浏览器中自动加载。

已包含空的 `requirements.txt` 文件供参考。

## 运行步骤

1. 进入项目目录：
```bash
cd malaysia-tourism-visualization
```

2. 启动HTTP服务器：
```bash
python3 -m http.server 8000
```

3. 打开浏览器访问：
```
http://localhost:8000/index.html
```

## 项目结构

```
malaysia-tourism-visualization/
├── index.html
├── style.css
├── data/
└── README.md
```
---
