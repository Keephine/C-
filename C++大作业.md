# C++大作业报告
---
学号：18062007
姓名：潘虹羽

## 实验过程

### 步骤一
#### 按照[快速使用手册](https://github.com/vesoft-inc/nebula/blob/master/docs/manual-CN/1.overview/2.quick-start/1.get-started.md)的提示，
#### 通过[编译源码](https://github.com/vesoft-inc/nebula/blob/master/docs/manual-EN/3.build-develop-and-administration/1.build/1.build-source-code.md)的方式安装[Nebula Graph](https://github.com/vesoft-inc/nebula)

### 步骤二
#### 修改代码后build

![](https://github.com/Keephine/C-/blob/master/3.png)

build完成后如图。

#### 查看修改的文件
```
git status
```

![](https://github.com/Keephine/C-/blob/master/11.png)

#### 查看修改的代码
```
git diff
```

![](https://github.com/Keephine/C-/blob/master/22.png)

#### 运行代码

![](https://github.com/Keephine/C-/blob/master/4.png)

出现error，重新检查代码，发现是更改的数组原本长度为2，但我在里面放了3个字符串，

#### 修改代码，重新build

![](https://github.com/Keephine/C-/blob/master/y.png)

#### 重新查看修改

![](https://github.com/Keephine/C-/blob/master/x.png)

![](https://github.com/Keephine/C-/blob/master/x1.png)

#### 运行代码

![](https://github.com/Keephine/C-/blob/master/z.png)

运行成功。

### 步骤三
#### 上传至Github，并提交一个pull request

![](https://github.com/Keephine/C-/blob/master/QQ%E6%88%AA%E5%9B%BE20191227143931.png)

push成功。

![](https://github.com/Keephine/C-/blob/master/QQ%E6%88%AA%E5%9B%BE20191227153112.png)

pull request

## 总结心得
选这门课的时候原本预想的是像学校必修的C语言课一样，换一门语言做一些简单的程序。但事实上学的东西比我想象中要难很多（虽然老师可能不这么认为）。凭着自己的任性最终也没有退选这门课。但其实上得也不认真。

不过，借由这次机会，了解了编程语言还有代码风格，在老师的带领下接触了Github，了解了有这么一个平台。为了做大作业，也是自己搜教程，安装了虚拟机，接触了linux系统。虽然过程简单，但因为自己的不断试错和撞墙，花费了很长的时间。从装虚拟机到make完成的过程花费了两天，但知识和经验也因此变得更加记忆深刻。

关于linux系统，到最后也只会几个简单的命令，但有了这一次尝试，也有了好好入门学习的信心。

十分感谢老师帮忙拉开了探索开源世界的大门的门缝！
