<!--
$theme: gaia
template: gaia
-->

Unix GNU/Linux基础

二、Unix家谱与GNU/Linux<p style="text-align:right;font-size:28px;margin-right:50px;color:#cFc;">:star: by calidion</p>
======================================================================================================================

---

Unix的家谱
==========

[![](images/Unix-Family.png)](https://i.stack.imgur.com/G2Xri.png)

---

Linux的家谱/发行版
==================

[![](./images/Linux-Distro.png)](./images/Linux-Distro.png)

---

常见的Linux发行版
=================

1.	[Ubuntu](https://www.ubuntu.com/)
2.	[Debian](https://www.debian.org/)
3.	[CentOS](https://www.centos.org/)
4.	[Arch](https://www.archlinux.org/)
5.	[Open SUSE](https://www.opensuse.org/)
6.	[Fedora](https://getfedora.org)
7.	[manjaro](https://manjaro.org/)

---

常见的桌面操作系统
==================

1.	[Ubuntu](https://www.ubuntu.com/)
2.	[Elementary OS](https://elementary.io)
3.	[Mint](https://www.linuxmint.com/)
4.	[Deepin](https://www.deepin.org/)
5.	[Tails](https://tails.boum.org/)

---

不同的Linux发行版有什么区别？
=============================

1.	目标用户不同
2.	依赖处理方式不同
3.	桌面套件不同以及裁剪后的效果不同
4.	包的管理工具不同（apt, yum, pacman)
5.	软件包的安装目录结构不尽不同

---

如果选择一个适合自己的Linux？
=============================

通常可以采用以下策略

1.	新手，日常工作使用 推荐Ubuntu, Mint, Deepin, Manjaro等主流桌面软件

2.	服务器 Ubuntu, CentOS, Debian等

3.	可控制性强, 高性能 Arch, Gentoo, LFS

---

Linux还是GNU/Linux？
====================

Linux本质只是一个内核 成为操作系统需要很多外部环境

首先就是要能编译Linux平台的软件，通常可以选择的套件只有GCC 其次是Shell环境，通常也是GNU的产品 同时还包括图形服务器X系统和桌面系统（GNOME，KDE） 而基本上Linux发行版最小必须包括一个Shell，也就是GNU的Shell 所以通常我们需要称Linux为GNU/Linux

---

GNU/Linux支持者的观点

=== 1. 光有Linux无法成为一个操作系统 2. 光有内核无法运行 3. 从Linux的发展来看，主要是因为GNU的存在，创造了Linux发展的机会 4. linux在遵从GPL之前并没有人关注

Debian首先支持GNU/Linux

---

Linux支持者的观点
=================

Linux Torvalds的观点：

Well, I think it's justified, but it's justified if you actually make a GNU distribution of Linux ... the same way that I think that "Red Hat Linux" is fine, or "SuSE Linux" or "Debian Linux", because if you actually make your own distribution of Linux, you get to name the thing, but calling Linux in general "GNU Linux" I think is just ridiculous.

---

我的看法
========

1.	Linux确实只是内核
2.	GNU的内核Mach一直没有进展
3.	将Linux与GNU合并构成了基本的Unix操作系统
4.	所以两个部分都是非常重要的。
5.	支持GNU/Linux的说法
6.	用户所接触的东西大部分核心工具是GNU的成果

---

宏内核 vs 微内核
================

#### 宏内核（Monolithic kernel）

将内核的所有的代码放在一个地址空间

#### 微内核（Micro kernel）

只将非常重要的IPC，基本定时器，基本的内存处理，IO原语操作等少量功能放在内核，其它的功能分布于不同的服务之中

---

宏内核的优势与劣势
==================

#### 优势

处理速度快

#### 劣势

内核容易因为其它内核模块的不稳定而不稳定 移植不便 内核大小不断增加

#### 案例

DOS，windows 98, Linux

---

微内核
======

#### 优势

内核不容易崩溃 移植性好 内核小

### 劣势

处理速度略慢

#### 案例

Windows NT, Mac os Mach, Minix

---
