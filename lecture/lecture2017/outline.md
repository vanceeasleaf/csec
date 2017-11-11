# 2017 热导率模拟计算实验大纲

### 周阳 y_zhou@fudan.edu.cn

## Lecture 1

- 课程简介
    - 课程目标

- 分子动力学原理
    - 动力学方程
    - 积分算法
    - 边界条件和初始条件
    - 经验势
    - 各种系综的实现

- 分子动力学计算物理量
    - 能量
    - 温度
    - 压强
    - 对关联函数和径向分布函数
    - Example

- 作业
    - 编写一个代码，用Verlet算法数值求解N个Ar理想气体原子的牛顿方程
    - 验证玻尔兹曼速率分布
    
## Lecture 2

- 环境搭建和工具
    - Linux基本指令
    - gcc和代码编译
    - Makefile的编写
    - python 生成脚本并调用

- LAMMPS
    - LAMMPS是什么
    - LAMPPS的安装和使用

- LAMMPS脚本实例
    - 模拟构型的搭建 - box,domain,lattice命令
    - 分子性质的指定 - mass,potential命令
    - 初始条件和边界条件 - velocity,boundary命令
    - 让分子动起来和系综 - fix 命令族
    - 物理量的计算 - compute 命令族
    - 数据的输出 - dump 命令族

- 作业
    - 用lammps重复上次课的作业
    - 用lammps计算Ar理想气体的融化曲线，求出融化温度

## Lecture 3

- 热传导是什么
    - Fourier's Law

- 分子动力学计算热导率-原理
    - Direct Method
    - Muller-Plathe
    - Greek-Kubo
    - Compare

- LAMMPS计算热导率
    - langevin热浴和NVT热浴
    - 自关联计算
    - 粒子交换的实现

- Project 
    

- 作业 
    - 仔细阅读本节课涉及的lammps命令，弄清热导率计算的详细过程。
    - 开始课程大作业

  