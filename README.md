Flask blog
==========

Personal blog written using the Flask microframework.


准备工作
===============


1. 将本仓库克隆到本地
2. (可选) 使用virtualenv 创建虚拟环境
3. 使用 `pip install -r requirements.txt`安装所需的库，也可以手动安装

开发流程
-----------

1. 进入cloned文件夹，使用命令 `sqlite3 blog.db < schema.sql` 生成所需的数据库(window系统需要把sqlite 添加到环境变量中去)
2. 执行 `python exec.py`
3. 在浏览器中打开[主页](http://localhost:5800)


