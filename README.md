# Typora 伪装 LaTeX 中文样式主题改版

## 主题介绍

本主题基于 [Keldos-Li](https://github.com/Keldos-Li/typora-latex-theme/commits?author=Keldos-Li) 的 [LaTex 主题](https://github.com/Keldos-Li/typora-latex-theme) 进行改版。在保留原版的 LaTex 排版的基础上对部分细节以及配色进行了更改，意图提高用户体验。同时，也感谢 Keldos-Li 为我们提供的优质 Typora 主题。

## 主题更改

### LaTex Dark 主题的更改

原版的 Dark 主题个人觉得配色对比太过强烈，看久了眼睛容易难受。故该版本修改了原版深色主题整体色调，包括但不限于背景颜色、边栏颜色、代码块颜色、内联代码块颜色等，使得修改之后的整体配色更接近于 Typora 官方的 night 主题，配色更加柔和。

修改了原版的加粗效果，原版的加粗强调在深色主题下不够明显，改版对加粗后的字体进行了稍微的放大。

修改了代码块中的字体，将字体修改为`Consolas`。

新增了图表自动编号，表格与图片编号是根据二级标题进行索引的，为了使您的图标编号正常，在创建图表之前，**请确保您至少创建了一个二级标题**。

改版后的主题命名为`latex-night`。

### LaTex 主题的更改

原版的 LaTex 浅色主题十分优质，本项目对原版的 Latex 主题并未作过多修改。除了和`latex-night`主题一样新增了图表自动编号之外，还修改了内联代码的样式。

改版后的主题命名为`latex-light`。

## 主题预览

### LaTex Night 主题预览

![](https://cdn.jsdelivr.net/gh/n70huihui/Blog_Photo/latex-night-1.png)

![](https://cdn.jsdelivr.net/gh/n70huihui/Blog_Photo/latex-night-2.png)

### LaTex Light 主题预览

该主题与原版几乎一致，修改地方不多，故不作仔细展示。

## 安装指南

本项目只提供两份`css`文件，不提供主题所需要的字体文件。**该主题所需要的额外字体请前往原版主题链接中进行下载**。

使用该主题需要您使用 Typora 打开任意`.md`文件，在软件左上方选择“文件”，然后点击下拉框中的“偏好设置”，找到“外观”，最后点击“打开主题文件夹”，即可打开本地的 Typora 主题文件夹。然后把两份`css`文件复制粘贴进去，重启 Typora 即可。
