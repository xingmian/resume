# 个人信息
-	孙幸勉 s00442799
-	女 / 1992 / 硕士研究生 天津大学 控制科学与工程
-	2012实验室 / 中央软件院 / 欧拉部 / OS内核实验室


# 技能
		
- Linux C编程，shell脚本；
- 了解操作系统原理，如内存管理，文件系统，进程管理等模块
- 对虚拟化技术有一些简单了解，使用docker容器部署


# 项目经历

## 2018.3 - 2019.9 自研安全OS内核项目

> 内存管理模块特性开发，设计并实现页表优化特性，GP API开发及后期维护，并负责最后内存模块的交接工作。

- 页表优化特性
  为了实现节省内存，提高内存空间的利用率，分析当前页表的设计，发现物理页释放后，并没有检查页表项所在的页表是否可以释放，页表依然占用内存，由此造成内存浪费。针对这个问题，对页表的管理做了优化，使得无用的页表可以释放，提高内存空间的利用率。经对比，系统可用内存占比明显提高。

- GP API开发

  承接下游 GP API 内存相关接口开发的需求，开发多个接口

- 内存模块交接工作

  交接期间，开展分享，介绍内存模块的框架目录及代码走读，对后期出现的问题提供解决思路，帮助下游快速上手。

## 2019.10 - 2020.10 鸿蒙文件系统 procfs / sysfs 伪文件系统

> 文件系统 procfs / sysfs 小组开发成员，参与框架开发，添加节点并实现节点的读写，以及重构优化和问题单的分析解决

- 框架开发及填充节点

  实现 procfs 模块动态创建pid及tid目录下的节点，及时响应下游对节点的需求，实现读写。
  
  实现 sysfs 模块中文件的读写操作的具体流程，并封装接口，简化其他模块使用sysfs的操作。

- procfs / sysfs 的重构优化

  随着节点的增加，节点处理存在大量重复代码，对此，抽取公共接口，使代码更清晰明了。交付期间解决问题单20+，保障了交付质量。

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
