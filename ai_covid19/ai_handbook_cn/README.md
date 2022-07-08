# 本书的阅读指南

> **动书** 是为了方便使用人工智能、增强现实、虚拟现实、物联网等数字教科书而开发的。这本互动书是ActionBook系列的第一本出版物 <https://yuanzhuo.bnu.edu.cn/actionbook>

本书以简单有趣的方式向9至15岁的孩子介绍人工智能。它还介绍了一些基于人工智能的解决方案的生动故事，这些解决方案是为了对抗流行病而开发的。此外，本书还通过展示简单的编程代码，让孩子们可以在JupyterLab环境上使用和实现，从而提供了关于人工智能的实践学习体验。

在读本内容上（`章`、`节`和`故事`）使用了三个年龄标签。每个标签表示该内容的年龄适宜性，说明如下:

- ![9](https://img.shields.io/badge/Age-9%2B-brightgreen) 标签标注了适合9岁以上读者阅读的章节。

- ![11](https://img.shields.io/badge/Age-11%2B-blueviolet) 标签标注了适合11岁及以上读者阅读的章节。

- ![13](https://img.shields.io/badge/Age-13%2B-9cf) 标签标注了适合13岁及以上读者阅读的章节。

读本各章、节和故事的年龄适宜性是根据Coh-Metrix软件和几位人工智能老师的意见确定的。Coh-Metrix是一种计算工具，可以产生文本语言和话语表征的指数（Graesser等，2004；McNamara等，2014）。所产生的输出值可以用许多不同的方式来研究交互式图书文本的难度、可读性和心理表征的一致性等。

文中的每个 "粗体字"术语都有一个文本框定义，旨在为读者进一步解释该术语。此外，在每一节的最后，都以小测验或思考题的形式给出了一个练习，以帮助读者练习该节所获得的知识。
  
该读本也可以供其他不同年龄段的人阅读，即使他们可能没有任何关于人工智能相关知识。家长和老师也可以利用这个读本向青少年介绍人工智能，引导他们与代码互动。

---

### 在这本互动书中使用JupyterHub

> [!NOTE]
> 推荐使用浏览器: **Google Chrome**, **Microsoft Edge** 和 **Firefox**.

本书基于人工智能的交互式版本，读者可以与所介绍的内容和代码进行交互 (测试、修改和下载)借由平台： [Yuanzhuo Online Code Platform](https://code.yuanzhuo.bnu.edu.cn/).

在这本书中，你可以找到互动部分的章节: **2.3, 3.3, 3.4, 4.3 and 5.3**.

![微信图片_20220708100400](https://md.hass.live/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20220708100400.png)

你可以使用给定的 **用户名** `yuanzhuo` and **密码** `yuanzhuo`, 或者通过以下的指导 **创建你自己的服务器**.

#### 什么是JupyterHub

JupyterHub是为多个用户提供Jupyter Notebook服务的最佳方式。它可以用于学生班级、企业数据科学小组或科研小组。它是一个多用户Hub，可以生成、管理和代理多个单用户Jupyter笔记本服务器的实例。
Jupyter Notebook是一个开源的Web应用程序，允许您创建和共享包含实时代码、方程、可视化和叙述性文本的文档。用途包括：数据清理和转换、数值模拟、统计建模、数据可视化、机器学习等。

#### 如何注册并登录平台

1.点击 [Yuanzhuo Online Code Platform](https://code.yuanzhuo.bnu.edu.cn/)

2.点击‘联系管理员’或直接访问[发送私信](https://yuanzhuo.bnu.edu.cn/message/send/)申请开通账号

![微信图片_20220708100933](https://md.hass.live/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20220708100933.png)

3.通过你的用户名和密码进行登录

4.点击 **My Server**,您可以从本页面下载源码上传到您的服务器.

![myserver](http://yuanzhuo.bnu.edu.cn/files/default/2020/07-20/170700413632130717.png)

如果您想安装其他软件包，请点击新建-终端，我们支持用户通过以下方式安装新的软件包

```bash
pip3 install --user <package name>
```

强烈建议使用Anaconda虚拟环境。

```bash
echo 'export PATH=/opt/anaconda/bin:$PATH' >> ~/.bashrc && source ~/.bashrc
conda create -n myspace
conda activate myspace
# 如需使用公共内核，需要安装ipykernel.
conda install ipykernel
```

---

### 权利和许可

此出版物在遵循共享3.0 IGO (CC-BY-SA 3.0 IGO）许可证 (<http://creativecommons.org/licenses/by-sa/3.0/igo/>)下提供开放访问

![feng1-cc](https://md.hass.live/feng1-cc.png)

#### 请按以下方式引用该作品

> 黄荣怀，刘德建，胡祥恩，Tlili, A，翁仲铭，樊磊，罗明勇，姚茜，Shubeck, K，张香玲，陈虹宇（2020）.人工智能助力新冠疫情防控网络互动读本.北京：北京师范大学智慧学习研究院.

---

### 联系我们

如果您有任何问题，请发送电子邮件到 `yuanzhuo@bnu.edu.cn`.
