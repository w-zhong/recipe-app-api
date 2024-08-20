# recipe-app-api

### 创建docker容器

`docker compose build`

### 使用flake8 lint代码

`docker compose run --rm app sh -c "flake8"`

### 创建django项目

`docker compose run --rm app sh -c "django-admin startproject app ."`

### 启动django项目
`docker compose up`