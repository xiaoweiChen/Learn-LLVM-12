# Learn LLVM 12
A beginner's guide to learning LLVM compiler tools and core libraries with C++ (*使用C++学习LLVM编译器和核心库的初学者教程*)

* 作者：Kai Nacke

* 译者：陈晓伟

* 原文发布时间：2021年5月28日 (来源亚马逊)

> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

**Learn how to build and use all parts of real-world compilers, including the frontend, optimization pipeline, and a new backend by leveraging the power of LLVM core libraries**

#### Key Features

- Get to grips with effectively using LLVM libraries step-by-step
- Understand LLVM compiler high-level design and apply the same principles to your own compiler
- Use compiler-based tools to improve the quality of code in C++ projects

#### Book Description

LLVM was built to bridge the gap between compiler textbooks and actual compiler development. It provides a modular codebase and advanced tools which help developers to build compilers easily. This book provides a practical introduction to LLVM, gradually helping you navigate through complex scenarios with ease when it comes to building and working with compilers.

You'll start by configuring, building, and installing LLVM libraries, tools, and external projects. Next, the book will introduce you to LLVM design and how it works in practice during each LLVM compiler stage: frontend, optimizer, and backend. Using a subset of a real programming language as an example, you will then learn how to develop a frontend and generate LLVM IR, hand it over to the optimization pipeline, and generate machine code from it. Later chapters will show you how to extend LLVM with a new pass and how instruction selection in LLVM works. You'll also focus on Just-in-Time compilation issues and the current state of JIT-compilation support that LLVM provides, before finally going on to understand how to develop a new backend for LLVM.

By the end of this LLVM book, you will have gained real-world experience in working with the LLVM compiler development framework with the help of hands-on examples and source code snippets.

#### What you will learn

- Configure, compile, and install the LLVM framework
- Understand how the LLVM source is organized
- Discover what you need to do to use LLVM in your own projects
- Explore how a compiler is structured, and implement a tiny compiler
- Generate LLVM IR for common source language constructs
- Set up an optimization pipeline and tailor it for your own needs
- Extend LLVM with transformation passes and clang tooling
- Add new machine instructions and a complete backend

## 作者简介

Kai Nacke is a professional IT architect currently living in Toronto, Canada. He holds a diploma in computer science from the Technical University of Dortmund, Germany. His diploma thesis about universal hash functions was recognized as the best of the semester.

He has been working in the IT industry for more than 20 years and has great experience in the development and architecture of business and enterprise applications. In his current role, he evolves an LLVM/Clang-based compiler.

For some years, he was the maintainer of LDC, the LLVM-based D compiler. He is the author of D Web Development, published by Packt. In the past, he was also a speaker in the LLVM developer room at the Free and Open Source Software Developers' European Meeting (FOSDEM).



## 审评者介绍

Suyog Sarda is a professional software engineer and an open source enthusiast. He focuses on compiler development and compiler tools. He is an active contributor to the LLVM open source community. Suyog was also involved in code performance improvements for the ARM and x86 architectures. He has been a part of the compiler team for the Tizen project. His interest in compiler development lies more in code optimization and vectorization. Previously, he has authored a book on LLVM, titled LLVM Cookbook, published by Packt. Apart from compilers, Suyog is also interested in Linux kernel development. He published a technical paper titled Secure Co-resident Virtualization in Multicore Systems by VM Pinning and Page Coloring at the IEEE Proceedings of the 2012 International Conference on Cloud Computing, Technologies, Applications, and Management at the Birla Institute of Technology, Dubai. He earned a bachelor's degree in computer technology from the College of Engineering, Pune, India.



## 本书相关

* github翻译地址：
* 本书代码：https://github.com/PacktPublishing/Learn-LLVM-12