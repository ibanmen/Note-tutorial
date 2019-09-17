<!--
$theme: gaia
template: gaia
-->

Unix GNU/Linux基础

一、创世纪<p style="text-align:right;font-size:28px;margin-right:50px;color:#cFc;">:star: by calidion</p>
=========================================================================================================

---

Unix的产生
==========

否定之否定的成果 1. Unix的祖辈***兼容分时系统(CTSS, Compatible Time-Sharing System)*** 小而简单

1.	Unix的父辈***Multics*** 试图建立一个具备复杂功能的系统，但不幸失败

2.	Unix 精减，分时，可远程，鼓励交流 首次实现在小型机上的编译能力

---

Unix创世纪(1969-1971)
=====================

<p style="position: absolute;right: 0px; top: 50px;z-index: -1"><img src="./images/Ken_n_dennis.jpg"/>
</p>

1.	创始人 Ken Thompson 贝尔实验室(Bell Labs) Multics项目成员

2.	联合创始人(Dennis Ritchie) C语言的发明者 阐述了理念：伙伴关系，远程访问，分时系统，鼓励交流 将计算机看成是社区=》导致（1969年)互联网前身ARPANET的出现。

3.	诞生所使用的机器（PDP-7）

---

Unix名称来的来源
================

1.	最初缩写是UNICS 即 Uniplexed Information and Computing Service
2.	而Multics是 Multiplexed Information and Computing Service 的缩写
3.	Ritchie的看法

“一个有点反叛Multics味道的双关语”

---

Unix的价值
==========

1.	第一个能让程序员直接坐在机器旁，就能让灵感转化成为程序并测试的系统
2.	很多程序员自愿为它开发

---

C语言以及Unix的进化
===================

1.	最初Unix是基于汇编编写的
2.	应用程序使用汇编与B语言混合编写
3.	Dennis Ritchie在B语言之上添加数据类型与结构并形成了C语言
4.	1973年，使用C语言重写了Unix
5.	可移植性的操作系统理念开始显现
6.	受到各大学术机构的欢迎，大量学校参与改进
7.	商业化初现端倪

---

TCP/IP与Unix内战
================

1.	Unix开源优势与TCP/IP项目 国防部高级研究计划局（DARPA，Defense Advanced Research Projects Agency) 促成了Unix与Internet的融合
2.	专利问题困扰Unix

源头：Bell Labs（ AT & T） 主要贡献者: a. 加州伯克利(BSD) 源码4万美元一份 b. SUN微系统：开创了工作站产业

---

Unix的分裂
==========

1.	产业化破坏了源码的自由交流
2.	商业博弈追求的差异化导致接口不统一
3.	Unix大战 System V（AT & T） vs. BSD（Berkeley) ---

战争中的一丝惊喜
================

1986年，Perl语言的发明（Larry Wall) 1985年，GNU宣言发布(Richard Stallman) 1985年， X Window源码发布，成为所有厂家的合作区，并成为事实的Unix图形引擎 1983年，接口标准化开展，即后来的IEEE的POSIX标准，结合BSD的socket规范，基本就是现代的Unix 1987年，GNU C的编译器问世 1985年，IBM发现了4G寻址空间的386，使Unix的PC化成为可能 1986年，康柏（Compaq)发布基于386的Unix主机，成为第一个Unix的PC机

---

Unix的黑暗时代（1989-1993）
===========================

1.	微软统治桌面，Unix无力抗挣
2.	优雅的Moto芯片，输给了Intel丑陋但是廉价的处理器
3.	GNU没有开发出来内核
4.	微软对软件世界的侵害越来越明显

---

Unix的进击（1991-1995）
=======================

1.	1990年William Jolitz将BSD移植到了386的机器上,但是随后退出386-BSD项目，并毁掉了自己的成果。原因是专利的问题，导致了源码无法自由的发布。
2.	1991年8月，Linus Torvalds宣布了Linux项目。 原因是Sun Unix太贵 不知道有386BSD项目
3.	开源BSD受专利诉讼的影响，导致开发者转向了Linux

4.	同时BSD分裂成三个方向，导致了BSD的没落

---

梦之Unix-Linux
==============

<p style="position: absolute;right: 0px; top: 50px;z-index: -1"><img width="200px" src="./images/tux.svg"/>
</p>

1993年时Linux已经具备： 1. internet 2. X系统(X window) 3. GNU 4. 其它软件包 5. 支持PC（现在基本支持所有可用的计算机系统）

传统的商业Unix的影响力日趋下降

---

Unix的黑客与极客文化
====================

1.	Unix传统
2.	黑客文化
3.	开源运动

三者通常有着很微妙的关系

---

黑客的含义
==========

1.	黑客最早来源于MIT 用于表达精巧但无害的恶作剧（hacks) 那么喜欢这样做的人就被称为是黑客(hacker)

2.	Unix程序员学会了TCP/IP后，也互称“黑客”

3.	与现在入侵别人电脑的黑客完全是不同的概念

---

极客(Geek)
==========

<p style="position: absolute;right: 0px; top: 50px;z-index: -1"><img src="./images/LOTRFOTRmovie.jpg"/>
</p>

具有黑客的技术实力 年轻 天资过人 并且通常是指男性 献身编程达到痴迷的程度 有嬉皮士范 喜欢看 J.K.K.写的《指环王》等小说

---

自由软件运动（1981-1991）
=========================

1.	创建人 Richard M. Stallman<p style="position: absolute;right: 0px; top: 50px;z-index: -1"><img src="./images/Richard_Matthew_Stallman_cropped.jpeg"/></p>

2.	项目名 GNU 操作系统

3.	事件 1985年发布了GNU宣言（GNU manifesto） 主张废除软件知识产权 发起自由软件以及自由软件运动 发布GPL（General Public License)

4.	最伟大的程序员 程序员中的社会主义者

---

什么是自由软件（Free Software)？
--------------------------------

1.	Free as in Freedom 在英文里存在混淆，在中文里，应该不会存在混淆。因为英文里的free可以理解成为免费。

2.	自由软件不是免费软件 它只关心软件源码的自由获取，即便需要付费

3.	GPL协议的强制源码开放与自由发布

	GPL是自由软件思想的核心，GPL要求所有它的衍生版修改后必须开放，开源；从而保证了软件的源码的永久可自由追溯。
	----------------------------------------------------------------------------------------------------------

	开源运动
	========

4.	多人发起 1998年，Jon "maddog" Hall 、Larry Augustin、Eric S. Raymond 和 Bruce Perens 等正式开始了开放源码运动。他们以各自卓越的专业基础极大地推动了这项运动的发展。

5.	主要思想来源是BSD体系的

6.	只关注源码的开放，而不关注源码修改后是不是开放

---

GNU是什么？
===========

<p style="position: absolute;right: 0px; top: 0px;z-index: -1"><img src="./images/heckert_gnu.small.png"/>
</p>

GNU是GNU is Not Unix的递归缩写

指GNU不是Unix，也就是没有Unix的专利问题的意思。 它的目标是创建一个不受专利危害的Unix。

GNU项目创造了很多重要的Unix软件。 最核心的是GCC, the GNU Compiler Collection，提供了Unix编译代码的基础

但是GNU的内核（叫HURD)一直空缺没有完成，直到Linux的出现

---

Linux游走于GPL与专利之间
========================

1.	Linux本身并不是GNU软件
2.	Linux在GNU的Richard M Stallman说服Linus Torvalds采用GPL后得到快速的发展
3.	Linux创建人并不完全认同GNU思想，但是认为GNU大部分时间是好的

---

“大教堂”与“集市”之争
====================

#### 大教堂

集权，封闭，受控，保密

#### 集市

分权，公开，精细的同们复审

---

开源运动 vs. 自由软件运动
=========================

自由软件运动是程序员开源的起点

开源运动让对源码的自由获取与软件专利之间作出妥协，只关注最初的开放源码，而不限制商业开发后不开放源码

都促进了软件的分享与繁荣

我们正在享受它们带来的自由与富足

---

自由软件VS开源软件
==================

1.	自由软件偏向于权力与政治
2.	开源软件关注代码本身
3.	自由软件可以保障基础软件不受第三方的控制
4.	开源软件无法做到
5.	自由软件对于最终用户有益
6.	开源软件可以促进开源软件在商业公司的应用

参考：https://www.gnu.org/philosophy/free-software-for-freedom.html
