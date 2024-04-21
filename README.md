# 高中物竞总结

## 简介

SHPC(Senior High Physics Competition)是一个LaTex排版语言的开源项目。`Chapters`目录下的各章节均包含TEX源文件和编译生成的PDF文件，`Resources`用于储存主文件引用的各种外部资源。

本项目用于总结我在高中物理竞赛学习过程中梳理的知识点和遇到的结论，也包括后来补充学习的部分内容。谨以此，追忆和纪念那段时刻奋斗的青春。

Copyright © 2024 by 申治洺

## 文章速览

已完成：无

进行中：
- 平面极坐标、柱坐标、球坐标下的加速度表达式 [PDF](https://github.com/Xiaoxiaomingbao/SHPC/blob/master/Chapters/PanPolarCoordinateSystem/chapter.pdf)
- 刚体力学总结 [PDF](https://github.com/Xiaoxiaomingbao/SHPC/blob/master/Chapters/RigidBody/chapter.pdf)

## About Git commits

It is always difficult to tackle generated PDFs in a LaTex project using Git. The functions of Git are severely constrained on binary files and PDFs are much larger than corresponding TEX files. Therefore, I will try to minimize the times of commits containing PDFs. If I commit a PDF, I will write "PDF included in commit" in the commit message.

## About IDEA TeXiFy

Configuration templates of IDEA extension TeXiFy:
- Compiler `XeLaTex`
- PDF viewer `Sumatra`
- Main file to compile _empty is okay_
- Directory for output files `{mainFileParent}`
- Output format `PDF`

With configurations above, pushing the gutter icon next to `\begin{document}`, we can generate PDF and other auxiliary files in the same directory as TEX. And we no longer need to add run/debug configuration for a single main file.
