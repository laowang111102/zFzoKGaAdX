# 前言

本项目为基于Spring Boot的校园社团信息管理系统，适用于高校内的各种社团组织，实现社团成员信息管理、活动发布、资料共享等功能。此项目旨在为学习Java开发的学生提供一个实战案例，以便更好地掌握Java相关技术。

## 内容介绍

本项目主要分为以下几个模块：

1. 用户模块：负责实现用户的注册、登录、个人信息管理等功能。
2. 社团模块：实现社团的创建、修改、查询、解散等操作。
3. 活动模块：负责活动的发布、修改、查询、报名等功能。
4. 资源模块：用于上传、下载、分享社团资料。

各模块之间相互协作，为用户提供一个便捷的校园社团信息管理平台。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为社团模块中查询社团列表的核心代码：

```java
@RestController
@RequestMapping("/api/club")
public class ClubController {

    @Autowired
    private ClubService clubService;

    @GetMapping("/list")
    public ResponseEntity<List<Club>> listClubs() {
        List<Club> clubs = clubService.listClubs();
        return ResponseEntity.ok(clubs);
    }
}
```

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/308197/40/26094/125822/689c9955Fa84cc666/f3d664ca63e1cd78.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/316104/13/26000/26546/689c9931Fba61193e/ed18a80cacd0e1fb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/317655/16/25192/75029/689c9931F154e0480/2834977729d87174.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/328456/18/4214/32871/689c9932F971a50cd/b577982ca139a9ac.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311526/29/26078/18063/689c9932F6d96e137/9dcc0f7dc9f5066b.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/288656/28/13603/52236/689c9934F99191260/73f504a1dc20f04a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/316163/12/25664/31564/689c9934F167e2675/a3e03f621a1892e8.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/318033/5/24484/19805/689c9935F20268711/35d5eccee0d53da2.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/312628/20/26022/29634/689c9936Fa9b0f5b7/4971ebd5bdc75efa.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/317683/28/24362/74859/689c9937Fea2d092b/1620b32c3134c166.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
