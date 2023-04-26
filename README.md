# Marp-Theme-JCUT：荆楚理工学院 Marp 主题

本仓库是基于 Marp 制作的荆楚理工学院主题，借助 Marp 的帮助，可以使用 Markdown 编写各种课程、汇报的 slide。

许多内容参考了 ：

1. [@BeWaterMyFriend7](https://github.com/BeWaterMyFriend7) 的 [Marp-Theme-UCAS](https://github.com/BeWaterMyFriend7/Marp-Theme-UCAS) 主题，对此表示由衷的感谢。

2. [@Tseing](https://github.com/Tseing) 的 [Marp Theme for NKU](https://github.com/Tseing/Marp-Theme-NKU) 主题，对此表示由衷的感谢。


点击[这里](https://github.com/Tseing/Marp-Theme-NKU/blob/master/docs/NKUmarp.pdf)的 pdf 文件可以看到完整的主题模版。

该主题的样式定义在 `./themes/JCUT.css` 中，如果你掌握 css 语法，可以尽情修改里面的样式。针对于某一页的样式，请使用 Marp 提供的局部样式修改。

关于 Marp 中特殊的语法，如果你已经学会 Markdown 语言，相信很容易就能学会，我是在[这里](https://caizhiyuan.gitee.io/categories/skills/20200730-marp.html)学会的。

更详细的内容请参考[Marp 官方文档](https://marpit.marp.app/)或[源码](https://github.com/marp-team/marp-vscode/#readme)。

# 文件结构

```
Marp-Theme-JCUT
├─ docs              // 导出的 pdf 文件
│  └─ JCUTmarp.pdf
├─ images            // 主题使用到的图片
│  ├─ attachment     // 可能能用上的图片
│  └─ example        // 示例图片，可删去
├─ JCUTmarp.md        // JCUT 主题模版（在这里写内容）
└─ themes
   └─ JCUT.css        // JCUT 主题样式文件

```

# 使用

1. 在 VS Code 中安装 Marp for VS Code 扩展;
2. 在 Marp-Theme-JCUT 下创建 .vscode 文件夹， 文件夹里创建 settings.json 文件，文件内编辑如下内容：
```
{
    "markdown.marp.themes": [
      "./themes/JCUT.css",
    ]
 }

```
3. 提供了两种字体：adobe std 黑体、Fandol黑体，放在根目录 Marp-Theme-JCUT 下；

4. 下载本仓库后，可以将 `docs` `example` 删去，复制 `JCTUmarp.md` 文件后在其中编写 slide，可以在 `images` 建立若干子文件夹用于存储需要导入 slide 的图片，便于项目分类管理。

# Some Pictures

![page 1](https://github.com/Tseing/Marp-Theme-JCUT/raw/master/images/example/page1.png)

![page 2](https://github.com/Tseing/Marp-Theme-JCUT/raw/master/images/example/page2.png)

![page 3](https://github.com/Tseing/Marp-Theme-JCUT/raw/master/images/example/page3.png)

![page 4](https://github.com/Tseing/Marp-Theme-JCUT/raw/master/images/example/page4.png)

![page 5](https://github.com/Tseing/Marp-Theme-JCUT/raw/master/images/example/page5.png)
