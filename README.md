# 前言

欢迎来到美食推荐系统的微信小程序+SpringBoot项目！该项目旨在为广大用户提供便捷的美食推荐服务，通过微信小程序和后端SpringBoot技术，实现用户与美食的快速匹配。以下是关于本项目的详细介绍。

## 内容介绍

本项目分为微信小程序和后端SpringBoot两部分。微信小程序负责用户交互，展示美食推荐结果；后端SpringBoot负责处理业务逻辑、数据存储等功能。以下是项目的主要功能：

1. 用户注册、登录、修改个人信息；
2. 美食分类浏览，根据用户喜好进行推荐；
3. 美食详情查看，支持评论、点赞、收藏；
4. 用户可查看自己的收藏和点赞记录；
5. 后台管理功能，包括美食管理、用户管理、评论管理等。

## 技术介绍

本项目采用以下技术栈：

- **语言：Java**
- **使用框架：Spring、SpringMVC、MyBatis、微信小程序**
- **前端技术：JS、Vue、CSS3、Uniapp**
- **开发工具：IDEA/Eclipse、Uniapp**
- **数据库：MySQL 5.7/8.0**
- **数据库管理工具：phpstudy/Navicat**
- **JDK版本：jdk1.8**
- **Maven：apache-maven 3.8.1-bin**
- **前端环境：Node.Js 12/14/16**

## 核心代码

以下是一段后端SpringBoot处理美食推荐的核心代码：

```java
// 省略import部分

@RestController
@RequestMapping("/api/recommend")
public class RecommendController {

    @Autowired
    private FoodService foodService;

    @GetMapping("/food")
    public List<Food> recommendFood(@RequestParam("userId") Integer userId) {
        // 根据用户喜好进行美食推荐
        List<Food> foods = foodService.recommendFoodByUserId(userId);
        return foods;
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/348738/34/3128/236142/68c6371fFa6f9466e/a96bdfae01b6b929.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/338243/32/10779/10557/68c636f6Fcefb7eef/dc4d26a99c939389.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348093/22/3194/43893/68c636f7F3d01150c/277d1c2ace11952a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337405/32/10390/73850/68c636f7F7d9d4096/380fdc991b93fc64.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337755/12/10530/40886/68c636f7Fa588d181/df2140bdcbc47525.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/350108/17/2362/36715/68c636f7Ffc7a87a3/a0ab4ae8b2802220.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/336011/38/9206/48803/68c636f8F85d0eee2/7cc7f99f5ad0d6ed.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336646/13/10523/54644/68c636f8F678bb7f8/44fa04312972eade.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/348117/40/3213/42118/68c636f8Fe84ca1d9/2638d445f874791d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337681/7/10649/204776/68c636f9Fbbf45bd1/e7323785574dbd5d.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
