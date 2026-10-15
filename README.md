# Flask-TodoList

[![CI](https://github.com/lianghui32/Flask-TodoList/actions/workflows/ci.yml/badge.svg)](https://github.com/lianghui32/Flask-TodoList/actions/workflows/ci.yml)

基于 Flask + SQLAlchemy 的简易待办事项（TodoList）应用，数据存储于 SQLite。

## 功能

- 添加待办：`POST /add`
- 切换完成/未完成状态：`/complete/<id>`
- 删除待办：`/delete/<id>`
- 首页渲染待办列表（[templates/index.html](templates/index.html) + [static/style.css](static/style.css)）

## 快速开始

```bash
pip install -r requirements.txt
python app.py        # 首次运行自动建表（todo.db）
```

浏览器访问 `http://127.0.0.1:5000`。

## 项目结构

```
app.py               Flask 应用与路由
templates/index.html 页面模板
static/style.css     样式
```

## License

[MIT](LICENSE)
