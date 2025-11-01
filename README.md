# 前言

欢迎来到本项目的Gitee页面！这是一个基于SpringBoot的医护人员排班系统，是本人毕业设计的一个实战项目。在整个项目开发过程中，我遵循了良好的编程规范和设计原则，力求为使用者提供高效便捷的排班体验。以下是本项目的详细介绍。

## 内容介绍

本项目是一款针对医护人员的排班系统，旨在帮助医疗机构高效地完成医护人员排班工作。通过本系统，可以实现自动排班、手动排班、班次调整等功能，大大减轻管理人员的工作负担。此外，系统还提供了完善的权限管理、日志记录等功能，确保数据安全和系统稳定运行。

## 技术介绍

本项目采用以下技术栈进行开发：

- **语言：Java**
- **使用框架：Spring Boot**
- **前端技术：JS、Vue、css3**
- **开发工具：IDEA/Eclipse**
- **数据库：MySQL 5.7/8.0**
- **数据库管理工具：phpstudy/Navicat**
- **JDK版本：jdk1.8**
- **Maven: apache-maven 3.8.1-bin**
- **前端环境：Node.Js 12\14\16**

## 核心代码

以下是本项目中的一段核心代码，展示了如何使用Spring Boot进行医护人员排班操作：

```java
// 查询所有医护人员
@GetMapping("/getDoctorsAndNurses")
public List<User> getDoctorsAndNurses() {
    return userService.getDoctorsAndNurses();
}

// 新增排班
@PostMapping("/addSchedule")
public Result addSchedule(@RequestBody Schedule schedule) {
    boolean flag = scheduleService.addSchedule(schedule);
    if (flag) {
        return new Result(true, "新增排班成功！");
    } else {
        return new Result(false, "新增排班失败！");
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

## 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/301814/3/20702/123043/689f3444Fa4b93c3c/5f594868800e930a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/312094/31/26590/68712/689f3433Fd5b12197/95f9e573d82d2e8a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/310455/20/26728/66936/689f3433Fae2e4948/f38bbbcaef06b8c7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/323923/20/5132/15458/689f3434F9eb4d949/5eee53044dff9db0.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/313226/11/26365/19200/689f3434Fb43bf239/1b230d9a65745165.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/297063/18/24768/26740/689f3435F8f793547/3ed0bef0f1b0c8e7.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/320753/20/24938/24093/689f3435F71fb000a/ce4448be5686ccc1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/322540/25/11186/22068/689f3435F1dc9f848/af4dc62a791a0644.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/319851/29/24798/21179/689f3436Fef1e5cd8/3d72f4190a449e25.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/307813/24/26328/21947/689f3436F153dde28/aab380ffa92cb565.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/310452/11/26428/72340/689f3437Fb8862a95/179808c0256762fc.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
