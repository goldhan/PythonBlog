# PythonBlog

[Python实战]( https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001432170937506ecfb2f6adf8e4757939732f3e32b781c000 )

## 文件结构

``` shell
PythonBlog <-- 根目录
├── LICENSE
├── README.md
├── backup <-- 备份目录
├── conf <-- 配置文件
├── dist <-- 打包目录
├── ios <-- 存放iOS App工程
└── www <-- Web目录，存放.py文件
    ├── static <-- 存放静态文件
    └── templates <-- 存放模板文件
```

## 需要的第三方库

- aiohttp  
    > 异步框架aiohttp
- jinja2
    > 前端模板引擎jinja2
- aiomysql
    > MySQL的Python异步驱动程序aiomysql

## 需要的服务

- MySQL