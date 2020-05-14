# SayHello

《[Flask Web 开发实战](http://helloflask.com/book)》 第7章留言版

Demo: http://sayhello.helloflask.com

![Screenshot](http://helloflask.com/screenshots/sayhello.png)


## 安装

git clone源码
```
$ git clone https://github.com/greyli/sayhello.git
$ cd sayhello
```

安装依赖
```

$ pip3 install -r requirements.txt
```


预先在DB生成20条假消息
```
$ flask forge

```

启动http服务

```
## Running on http://0.0.0.0:8080/
$ flask run -h 0.0.0.0  -p 8080 
```

在本地尝试访问服务

```
$ curl http://localhost:8080
```

通过浏览器访问服务

```
http://IP:8080
```




