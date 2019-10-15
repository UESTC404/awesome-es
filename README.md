# 项目介绍

这是一个电子科技大学软件学院本科阶段计算机体系结构学习&嵌入式开发的公开课/书籍/Blog/资料整理的项目，如果你有贡献的想法：

1. 可以直接提交Pull Request
2. 如果你是嵌入式工作室成员，请联系[@starFalll](https://github.com/starFalll)（fyxformal@gmail.com）,[@StevenXu98](https://github.com/StevenXu98)（steven_xu98@163.com）等[UESTC404](https://github.com/UESTC404)组织的所有者，邀请你加入 UESTC404 中

# 学习资源分享

- 推荐的学习主线：

| 时间  | 内容 |
| ----- | ---- |
| 大一上 | C语言  |
| 大一下 | 数据结构和算法， STM32裸板开发，项目实战 |
| 大二上 | arm体系架构([嵌入式linux](#嵌入式linux))，linux系统编程，计算机组成原理， 编译原理， 项目实战 |
| 大二下 | C++， 实时操作系统RTOS，linux内核与驱动([嵌入式linux](#嵌入式linux))，[操作系统](#操作系统)，项目实战 |
| 大三上 | [项目实战](#项目实战)，[找实习](#找实习) |
| 大三下 | 企业实习/教研室科研/海外交换 |

- 欢迎大家随时更新
- 参考阅读
  - [机器人工程师学习计划](https://zhuanlan.zhihu.com/p/22266788)
  - [技术专精与广博的一些思考](https://zhuanlan.zhihu.com/p/75522108)
  - [电子科技大学资源共享平台](https://github.com/UESTC-Course/uestc-course)
  - [清华大学计算机系课程攻略](https://github.com/PKUanonym/REKCARC-TSC-UHT)
  - [浙江大学课程攻略共享计划](https://github.com/QSCTech/zju-icicles)
  - [中国科学技术大学课程资源](https://github.com/USTC-Resource/USTC-Course)
  - [上海交通大学课程资料分享](https://github.com/CoolPhilChen/SJTU-Courses)

## 技能图谱
### 基础知识
作为一名软件学院的本科生，必须牢牢掌握以下计算机相关的知识：

|技能点名称|技能点内容|
|--|--|
|[编程语言](#编程语言)|[C语言](#C语言), [C++](#C++), [Python](#Python)|
|[算法和数据结构](#算法和数据结构)||
|[软件工程](#软件工程)||
|[编译原理](#编译原理)||
|[计算机体系结构](#计算机体系结构)||
|[操作系统](#操作系统)||
|[计算机网络](#计算机网络)||

### 嵌入式方向
如果你对嵌入式方向有兴趣，需要掌握以下技能：

|技能点名称|技能点内容|
|--|--|
|开发平台|CPU:Intel x86, ARM x86|
||[MCU编程](#MCU编程): C51, STM32|
||FPGA||
|[嵌入式开发软件](#嵌入式开发软件)|Keil uVision, STM32Cube, jtag debugger|
|[嵌入式Linux](#嵌入式Linux)|Bootloader, driver, ...|
|[实时操作系统](#实时操作系统)|uCOS, ROS|
|外设|Timer, ADC / DAC, ROM / RAM, PWM, I/O / GPIO, ...|
|执行器|电机(步进, 无刷, 舵机，...)，电调|
|传感器|陀螺仪，超声波，红外, ...|
|电子元件|电容，电阻，开关，二极管, ...|
|通信协议|Bluetooth, Zigbee, Wifi, UART, TCP, UDP, I2C, ...|
|电路|焊电路, PCB设计|

## 编程语言
### C语言

书籍推荐：

|名称|作者|介绍|
|-|-|-|
| [C语言程序设计现代方法](https://book.douban.com/subject/2280547/) |K. N. King|入门推荐读物，讲解清晰|
| [C与指针](https://book.douban.com/subject/3012360/) |[Kenneth A·Reek](https://book.douban.com/author/1715767/)|进阶读物，“C语言三剑客”之一|
| [C陷阱与缺陷](https://book.douban.com/subject/2778632/) |[凯尼格](https://book.douban.com/author/284407/)|进阶读物，“C语言三剑客”之一，重点讲解C中的注意事项|
| [C专家编程](https://book.douban.com/subject/2377310/) |[Peter van der Linden](https://book.douban.com/author/1176128/)|进阶读物，“C语言三剑客”之一|

资源推荐：


- [C 语言资源大全中文版](https://github.com/jobbole/awesome-c-cn)
- [The C build process](https://blog.feabhas.com/2012/06/the-c-build-process/)
### C++

书籍推荐阅读顺序：

|阅读顺序|名称|作者|介绍|
|-|-|-|-|
| 1 | [C++ Primer](https://book.douban.com/subject/25708312/) |[[美\] Stanley B. Lippman](https://en.wikipedia.org/wiki/Stanley_B._Lippman) / [美\] Josée Lajoie / [[美\] Barbara E. Moo](https://en.wikipedia.org/wiki/Barbara_E._Moo)|C++最经典教程|
| 2 | [Effective C++](https://book.douban.com/subject/5387403/) |[梅耶 (Scott Meyers)](https://book.douban.com/search/梅耶)|C++开发必读经典|
| 3 | [STL源码剖析](https://book.douban.com/subject/1110934/) |[侯捷](https://book.douban.com/author/104388/)|理解STL源码必读|
| 4 | [深度探索C++对象模型](https://book.douban.com/subject/1091086/) |[[美\] Stanley B·Lippman](https://book.douban.com/author/201520/)|从编译器层面认识C++对象模型|

资源推荐：

- [C++ 资源大全中文版](https://github.com/jobbole/awesome-cpp-cn)
- [CppTemplateTutorial](https://github.com/wuye9036/CppTemplateTutorial)
### Java
- [面向对象程序设计——Java语言 - 翁恺](http://www.icourse163.org/course/ZJU-1001542001#/info)
### Python
- [Python教程- 廖雪峰](https://www.liaoxuefeng.com/wiki/1016959663602400)
### 汇编 - X86
- [8086 assembly programming with emu8086](https://github.com/gurugio/book_assembly_8086)
### 汇编 - ARM
- [ARM Architecture Reference Manual, 2nd Edition](https://www.scss.tcd.ie/~waldroj/3d1/arm_arm.pdf)

## 算法和数据结构
|名称|作者|介绍|
|-|-|-|
| [数据结构](https://dsa.cs.tsinghua.edu.cn/~deng/ds/dsacpp/) |邓俊辉|国内质量最高的数据结构课程，推荐在MOOC上跟学，[教材链接](https://book.douban.com/subject/25859528/)|

## 工具链
### 版本控制：Git
- [Git教程- 廖雪峰](https://www.liaoxuefeng.com/wiki/896043488029600)

### 编译工具：Makelile
- [Make 命令教程](http://www.ruanyifeng.com/blog/2015/02/make.html)
- [GCC and Make](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html)
- [Managing projects with GNU Make](http://uploads.mitechie.com/books/Managing_Projects_with_GNU_Make_Third_Edition.pdf)

### 嵌入式开发软件
- Keil uVision
- STM32Cube
- jtag debugger

## MCU编程
### 51单片机
- [BY51DB开发板 51单片机代码](https://github.com/TairanHu/51-BY51DB)
### STM32
- [野火电子](https://github.com/Embdefire/products/wiki)
- [STM32F103C8 参考代码](https://github.com/avislab/STM32F103)
- [STM32F427 RoboMaster A板 BSP](https://github.com/RT-Thread/rt-thread/tree/master/bsp/stm32/stm32f427-robomaster-a)
### 树莓派
- [树莓派新手入门教程](http://www.ruanyifeng.com/blog/2017/06/raspberry-pi-tutorial.html)

## 嵌入式Linux

### 书籍推荐

|名称|作者|介绍|
|-|-|-|
|[LKD3](https://book.douban.com/subject/6097773/)|Robert Love|linux内核的设计与实现，非常经典的入门书籍。可帮助理解操作系统|
|[ELDD](https://book.douban.com/subject/3088263/)|Sreekrishnan Venkateswaran|linux设备驱动详细解读，稍难，是linux设备驱动相关的经典书籍。|
|Linux内核源代码情景分析|毛德操 / 胡希明|浙大毛教授著作。基于2.4内核，对代码有详细解读。虽2.4版本较老，但如此详细的解读也值得一读。|
| [The Design of the Unix Operating System](https://book.douban.com/subject/1768601/) |Maurice J. Bach||
| [Linux 内核揭秘](https://xinqiu.gitbooks.io/linux-insides-cn/content/index.html)|||
| [Linux Device Drivers, 3rd Edition](https://book.douban.com/subject/1723151/)|Jonahan Corbet||



## 编译原理

|名称|作者|介绍|
|-|-|-|
|[15-411/611 Compiler Design - CMU](https://www.cs.cmu.edu/~janh/courses/411/16/)|Jan Hoffmann|CMU的编译原理基础课程|
|[自己动手写编译器](https://pandolia.net/tinyc/index.html)|pandolia|实现一个简单的C编译器|

## 软件工程
- 编写文档： [Doxygen](http://www.doxygen.nl/), [Sphinx](http://www.sphinx-doc.org/en/master/)
- 代码质量：
  - C: [华为C语言编程规范](https://ilcc.gitbooks.io/wiki/StyleGuide/Huawei-C/index.html)
  - C++: [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
  - Java: [阿里巴巴Java开发手册](https://yq.aliyun.com/articles/69327)
  - Python: [PEP8](https://www.python.org/dev/peps/pep-0008/), [isort](https://pypi.org/project/isort/), [black](https://pypi.org/project/black/), [Pyre](https://github.com/facebook/pyre-check)
- 自动化测试: [Robot](https://robotframework.org/) 
- Code review: [Gerrit](https://www.vogella.com/tutorials/Gerrit/article.html)

## 计算机体系结构
|名称|作者|介绍|
|-|-|-|
| [Computer Organization and Design, Fifth Edition](https://book.douban.com/subject/25820786/)|David A. Patterson / John L. Hennessy|作者是图灵奖得主，提出RISC架构|

## 计算机网络
|名称|作者|介绍|
|-|-|-|
|[计算机网络(第6版)](http://book.douban.com/subject/26176870/)| James F.Kurose / Keith W.Ross ||

## 操作系统

| 名称                                                         | 作者 | 介绍                                                     |
| ------------------------------------------------------------ | ---- | -------------------------------------------------------- |
| [清华大学操作系统课程(2019)](https://chyyuu.gitbooks.io/os_course_info/) |      | 清华OS实验室的操作系统课程，课件、实验作业的质量都非常高 |

## 实时操作系统

|名称|作者|介绍|
|-|-|-|
|[μC/OS-III: The Real-Time Kernel for STM32](https://doc.micrium.com/pages/viewpage.action?pageId=10753180&preview=/10753180/12779577/100-uCOS-III-ST-STM32-003.pdf)|Jean J. Labrosse|经典实时操作系统, C语言编写|
|[AliOS Things](https://github.com/alibaba/AliOS-Things)||国产实时操作系统，阿里巴巴面向物联网领域开发|
|[TencentOS-tiny](https://github.com/Tencent/TencentOS-tiny)||国产实时操作系统，腾讯面向物联网领域开发|

## 项目实战
工作室往届的项目介绍：

|名称|年级|介绍|
|-|-|-|
|[Quadcopter](https://github.com/xxyyttxx/Quadcopter)|2015|基于STM32F411外设固件库的四轴keil5工程|
|[基于Tensorflow的树莓派智能识别机器人](https://github.com/starFalll/Raspbarry_Tensorflow_Robot)|2016|基于Tensorflow的树莓派智能识别机器人|
|[Quadcopter](https://github.com/Crabor/Quadcopter)|2017|基于STM32F401RE的四轴飞行器|

一些推荐参加的本科阶段的科技创新类项目 & 比赛：

|名称|介绍|
|-|-|
|[Google Summer of Code](https://summerofcode.withgoogle.com/)|每年3月份开始提交申请的proposal|
|[数学建模](http://www.math.uestc.edu.cn/mathmodeling/index.php)|要自学一下matlab|
|[Robomaster](https://www.robomaster.com/zh-CN/robo/overview)||
|[ACM](https://acm.uestc.edu.cn/)||
|嵌入式综合设计|在廖老师指导下做四轴飞行器|

## 找实习
- 找工作室前辈内推
- 刷题：[Leetcode](https://leetcode.com/)，[牛课网](https://www.nowcoder.com/)

