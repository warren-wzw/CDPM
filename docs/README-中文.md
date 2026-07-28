# CDPM 项目页：最简单使用方法

## 第一步：先在电脑上看效果

双击 `index.html`，浏览器就会打开页面。

## 第二步：换成你自己的图片

进入 `assets` 文件夹。

你可以直接覆盖下面这些文件：

- `teaser.svg`：首屏总览图
- `framework.svg`：网络框架图
- `result-rgbt.svg`
- `result-googlemap.svg`
- `result-pcb.svg`

最省事的办法：把你的 PNG 图片改成同名，例如 `teaser.png`，然后在 `index.html` 中把：

`assets/teaser.svg`

改成：

`assets/teaser.png`

## 第三步：改标题、作者和链接

右键 `index.html`，用 VS Code 或文本编辑器打开。

搜索以下内容并替换：

- `Structure-Aware Dense Matching...`
- `Co-author Name`
- `href="#"`：改成论文、代码、补充材料和数据集链接
- Abstract
- BibTeX

## 第四步：上传到你的 GitHub 主页仓库

你的主页仓库假设叫：

`warren-wzw.github.io`

在该仓库根目录建立一个文件夹：

`cdpm`

把本压缩包中的 `index.html` 和 `assets` 整体上传到 `cdpm` 中。

结构应当是：

warren-wzw.github.io/
  index.html
  cdpm/
    index.html
    assets/
      style.css
      main.js
      teaser.svg
      ...

上传完成后访问：

https://warren-wzw.github.io/cdpm/
