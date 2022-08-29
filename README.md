# vue-t/demo



## 下载使用

首先复制仓库链接, 下载仓库到本地

```xml
git clone
```

cmd命令(每个人知识储备程度不同,我就这样尽可能详细讲吧, 希望能帮到你) 进入到vue-ts-mall-demo文件夹

执行下面命令, 下载项目所需要的依赖

```
npm install
```

然后执行下面命令来启动项目

```xml
npm run serve
```

每个人网速或者npm的镜像不同, 可能需要等待一会儿, 如果没有什么问题, 会显示下面内容

![image-20220625153132677](https://firstbucket-1300448090.cos.ap-chengdu.myqcloud.com/cbz_book_images/image-20220625153132677.png)

打开浏览器输入地址

```xml
http://localhost:8081/
```

就可以进入系统

## 界面展示

输入http://localhost:8081/, 如果是首次进入, 会跳转到登录页面

登录页面展示

![image-20220625153342646](https://firstbucket-1300448090.cos.ap-chengdu.myqcloud.com/cbz_book_images/image-20220625153342646.png)

**用户名是 admin  密码是 123456**

登录成功后会进入系统主页面

系统主页面

商品列表

![image-20220625153447006](https://firstbucket-1300448090.cos.ap-chengdu.myqcloud.com/cbz_book_images/image-20220625153447006.png)

用户列表页面

![image-20220625153517445](https://firstbucket-1300448090.cos.ap-chengdu.myqcloud.com/cbz_book_images/image-20220625153517445.png)

角色列表

![image-20220625153535530](https://firstbucket-1300448090.cos.ap-chengdu.myqcloud.com/cbz_book_images/image-20220625153535530.png)


### 项目搭建

### 登录页面

### 登录逻辑

在登录成功之后, 会跳转到首页

![image-20220622162821112](https://firstbucket-1300448090.cos.ap-chengdu.myqcloud.com/cbz_book_images/image-20220622162821112.png)

同时, 可以查看本地localStorage, 保存了token信息

![image-20220622162531334](https://firstbucket-1300448090.cos.ap-chengdu.myqcloud.com/cbz_book_images/image-20220622162531334.png)

