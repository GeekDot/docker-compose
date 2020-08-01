<h2 align= center>  </h2>

<h5 align=right> 张懿 </h5>
<p align=right> 2020-07-23 </p>

### 一、准备工作

- 安装 Pyhon 3.8.1

- 安装 MySQL

- 安装 Docker

#### 二、启动 Docker

	cd docker/dev
	docker-compose up -d
	docker ps -a

4 个容器分别是

	mysql
	redis
	phpmyadmin
	phpredmin
	
#### 三、登录可视化数据库

MySQL

	host：http://127.0.0.1:8080/
	user：root
	password：makemoney
	
Redis

	host：http://127.0.0.1:8089/
	user：admin
	password：admin