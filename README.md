# Learn LLVM 12
A beginner's guide to learning LLVM compiler tools and core libraries with C++ 

(*使用C++学习LLVM编译器和核心库的初学者教程*)

* 作者：Kai Nacke

* 译者：陈晓伟

* 原文发布时间：2021年5月28日 (来源亚马逊)

> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

学习如何构建和使用编译器，包括前端、流水线优化和利用LLVM核心库的强大功能构建新的后端编译器。

LLVM是为了弥合编译器理论和实际开发之间的差异而出现的。它提供了模块化的代码库和先进的工具，帮助开发人员轻松地构建编译器。本书提供了对LLVM的介绍，帮助读者在各种情况下构建和使用编译器。

本书将从配置、构建和安装LLVM库、工具和外部项目开始。接着，向您介绍LLVM的设计，以及在每个编译器阶段(前端、优化器和后端)的实际工作方式。以实际编程语言为例，学习如何使用LLVM开发前端编译器，并生成LLVM IR，将其交给优化流水线，并从中生成机器码。后面的章节将展示如何扩展LLVM，以及LLVM中的指令选择是如何工作的。在了解如何为LLVM开发新的后端编译器之前，将重点讨论即时编译问题和LLVM提供的JIT编译的支持情况。

阅读本书后，您将获得使用LLVM编译器开发框架的实际经验，并得到一些具有帮助性的实际示例和源代码片段。

#### 关键特性

- 学习如何有效地使用LLVM
- 理解LLVM编译器的高级设计，并将原则应用到自己的编译器中
- 使用基于编译器的工具来提高C++项目的代码质量

#### 内容纲要

- 配置、编译和安装LLVM框架
- 理解LLVM源码的结构
- 了解在项目中可以使用LLVM做什么
- 探索编译器是如何构造的，并实现一个小型编译器
- 为通用源语言构造生成LLVM IR
- 建立优化流水线，并根据自己的需要进行调整
- 使用转换通道和clang工具对LLVM进行扩展
- 添加新的机器指令和完整的后端编译器



## 作者简介

**Kai Nacke**是一名专业IT架构师，目前居住在加拿大多伦多。毕业于德国多特蒙德技术大学的计算机科学专业。他关于通用哈希函数的毕业论文，被评为最佳论文。

他在IT行业工作超过20年，在业务和企业应用程序的开发和架构方面有丰富的经验。他在研发一个基于LLVM/Clang的编译器。

几年来，他一直是LDC(基于LLVM的D语言编译器)的维护者。在Packt出版过《D Web Development》一书，他也曾在自由和开源软件开发者欧洲会议(FOSDEM)的LLVM开发者室做过演讲。



## 审评者介绍

**Suyog Sarda**是一名专业的软件工程师和开源爱好者，专注于编译器开发和编译器工具，是LLVM开源社区的积极贡献者。他毕业于了印度浦那工程学院，具有计算机技术学士学位。Suyog还参与了ARM和X86架构的代码性能改进，一直是Tizen项目编译团队的一员，对编译器开发的兴趣在于代码优化和向量化。之前，他写过一本关于LLVM的书，名为《LLVM Cookbook》，由Packt出版。除了编译器，Suyog还对Linux内核开发感兴趣。他在迪拜Birla Institute of Technology的2012年IEEE Proceedings of the International Conference on Cloud Computing, Technologies, Applications, and Management上发表了一篇题为《VM pin and Page Coloring Secure Co-resident Virtualization in Multicore Systems》的技术论文。



## 本书相关

* github翻译地址：https://github.com/xiaoweiChen/Learn-LLVM-12
* 本书代码：https://github.com/PacktPublishing/Learn-LLVM-12
* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html 

