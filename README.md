## Django搭建个人博客
![py3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) 
  [![](https://img.shields.io/badge/Django-2.0-brightgreen.svg)]()

使用Django快速搭建博客
### 环境
* Python: 3.X
* Django: 2.0.x
* MySQL
<font color=red >
* 特别注意依赖库的版本问题
* pip install Django==2.0.7
* pip install Pillow==7.1.0
* 等
</font>


### 特点

* 博客文章 `markdown` 渲染，代码高亮
* 第三方社会化评论系统支持(畅言)
* 三种皮肤自由切换
* 全局搜索
* 阅读排行榜/最新评论
* 多目标源博文分享
* 博文归档
* 友情链接
* 分享、打赏功能

### 下载
```
git clone 
https://github.com/lh500/blog01.git
```

### 安装
```
pip install -r requirements.txt  #安装所有依赖
setting.py配置自己的数据库
配置畅言：到http://changyan.kuaizhan.com/注册站点,将templates/message.html中js部分换成你在畅言中生成的js。
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

浏览器中打开<http://127.0.0.1:8000/>即可访问

## Screen Shots

* 首页
![首页](./doc/image/image1.png)

* 文章列表
![文章列表](./doc/image/image2.png)

* 文章内容
![文章内容](./doc/image/image3.png)
  


<font size=3 color=grenn face='华文彩云'>* 后台初始管理账号 *
<br>账号：Tim
<br>密码：Tim123456 
</font>
  
