# Reading guidelines of the book

> **ActionBook** is developed to facilitate digital textbooks using AI, AR, VR, IoT, etc. This interactive book is the first publication of ActionBook series on <https://yuanzhuo.bnu.edu.cn/actionbook>

This book introduces AI to children, between the age of 9 and 15, in an easy and fun way. It also presents vivid stories about some AI-based solutions that were developed to combat the pandemic. Furthermore, this book presents a hands-on learning experience about AI by showing simple programming code that children could use and implement on the JupyterLab environment.

Three age tags were used on the book content (`chapter`, `section` and `story`). Each tag denotes the age appropriateness of that content, as follow:

- ![9](https://img.shields.io/badge/Age-9%2B-brightgreen) tag highlights the sections that are appropriate for children of the age of nine and above.

- ![11](https://img.shields.io/badge/Age-11%2B-blueviolet) tag highlights the sections that are appropriate for children of the age of eleven and above.

- ![13](https://img.shields.io/badge/Age-13%2B-9cf) tag highlights the sections that are appropriate for children of the age of thirteen and above.

The age appropriateness for each of the book chapters, sections and stories was based on Coh-Metrix software and several AI teachers. Coh-Metrix is a computational tool that produces indices of the linguistic and discourse representations of a text (Graesser et al., 2004; McNamara et al., 2014). The produced output values can be used in many different ways to investigate the difficulty, readability and the coherence of the mental representation of the interactive book texts.

Additionally, a textbox definition was given to each “Bold” term in the text. This textbox aims to further explain that term for children. Furthermore, at the end of each section, an exercise was given in the form of a quiz or a reflection question, to help children practice the gained knowledge from that section.
  
It should be noted that this book can also be read by other people with different ages who may not have any background about AI. Parents and teachers can also use this book to introduce AI to their children or students respectively, and guide them to interact with the presented code online.

---

### Use JupyterHub in this interactive book

> [!NOTE]
> Recommended browser: **Google Chrome**, **Microsoft Edge** and **Firefox**.

The interactive AI-based version of this book, where readers can interact with the presented content and code (test, modify and download it), is powered by [Yuanzhuo Online Code Platform](https://code.yuanzhuo.bnu.edu.cn/).

In this book, you can find the interactive part on section **2.3, 3.3, 3.4, 4.3 and 5.3**.

![interpart](https://md.hass.live/2020-08-16-Xnip2020-08-16_18-55-40.png)

You can login with the given **username** `yuanzhuo` and **password** `yuanzhuo`, or you can read the instruction below and **create your own server**.

#### What is JupyterHub

JupyterHub is the best way to serve Jupyter notebook for multiple users. It can be used in a classes of students, a corporate data science group or scientific research group. It is a multi-user Hub that spawns, manages, and proxies multiple instances of the single-user Jupyter notebook server.
The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.

#### How to sign up and sign in on the platform

1.Click [Yuanzhuo Online Code Platform](https://code.yuanzhuo.bnu.edu.cn/)

2.Click ‘联系管理员’ or directly visit [send message](https://yuanzhuo.bnu.edu.cn/message/send/)to **元卓计划** to perform the application.

![微信图片_20220708101759](https://md.hass.live/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20220708101759.png)

3.Sign in with your username and password

4.Click **My Server**,You can upload the source code to your server downloaded from this page.

![myserver](http://yuanzhuo.bnu.edu.cn/files/default/2020/07-20/170700413632130717.png)

If you want to install other packages, click New-Terminal, we support user install new packages by

```bash
pip3 install --user <package name>
```

We strongly recommend you to use Anaconda private environment

```bash
echo 'export PATH=/opt/anaconda/bin:$PATH' >> ~/.bashrc && source ~/.bashrc
conda create -n myspace
conda activate myspace
# to use public kernel, ipykernel is required.
conda install ipykernel
```

---

### Rights and Permissions

This publication is available in Open Access under the Attribution-ShareAlike 3.0 IGO (CC-BY-SA 3.0 IGO) license (<http://creativecommons.org/licenses/by-sa/3.0/igo/>).

![feng1-cc](https://md.hass.live/feng1-cc.png)

#### Please cite the work as follows

> Huang, R., Liu, D., Hu, X., Tlili, A., Own, C.M.,Fan, L., Shubeck, K., Jemni, M. Zhang, X., Chen, H.Y. (2020). Interactive Book on Artificial Intelligence to Combat Pandemics: Vivid Stories in Prevention and Control of COVID-19. Beijing: Smart Learning Institute of Beijing Normal University

---

### Contact Us

If you have any issue, please contact us by sending e-mail to `yuanzhuo@bnu.edu.cn`.
