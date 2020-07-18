#### **新建项目**
1. 安装虚拟库：pip install pipenv
2. 安装指定django：pipenv install django==2.2.14
3. 创建新的项目：pipenv run django-admin startproject blogproject C:\project
4. 创建新的应用：pipenv run python manage.py startapp mysite
5. 修改settings.py的时区配置，添加应用
#### **设计模型**
1. 编写模型代码，配置数据库
2. python manage.py makemigrations
3. python manage.py migrate
4. admin中注册模型
5. 创建超级用户：python manage.py cteatesuperuser
#### 路由设计和编写视图
1. urls.py文件添加路由
2. 视图中添加相应的函数
3. 创建HTML页面文件
#### 前端页面设计
1. 编写HTML页面
2. 引用第三方前端框架
3. 添加静态文件和重写
#### Django表单
1. 新建forms.py，编写表单代码
2. 修改视图处理函数
3. 修改html页面
#### 添加图片验证码
1. 第三方模块实现
2. 修改相关配置文件、模板文件以及视图函数
#### session会话


