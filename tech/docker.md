## docker

### 第一章 容器的基本操作

> 创建 hello world 

​		

> 进行交互式操作

* 启动时进行交互：docker run -it  + image
* 跟已经运行的container交互: docker exec -it + image
* 参数说明
  1. -t: 在新容器里指定一个终端或伪终端
  2. -i：对容器进行标准输入和输出	   

> 后台运行和停止容器  

* 后台运行

  docker run -d + image

* 停止容器

  docker stop + containerId

> 指定访问端口   

​	docker run -p 5000:5000



### 第二章 镜像的基本操作

> 镜像管理

* 镜像列表

  docker image ls

* 镜像查找

  docker search tomcat

* 



