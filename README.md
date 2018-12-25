# XeLatex Template for ZJU Thesis

感谢[shuwei1204](https://github.com/shuwei1204/ZJUthesis)及各路前辈制作的原始版本。

由于macOS上的原生中文字体的与Windows并不相同，原始模板在macOS下会出现字体无法渲染等问题。
本模板在前人基础上作了部分改进，支持macOS。测试环境为MacTeX-2018，系统为macOS 10.14。

## 安装步骤

1. 首先安装[MacTex](https://www.tug.org/mactex/mactex-download.html)
2. （可选）安装[TexStudio](https://sourceforge.net/projects/texstudio/)，注意在Preferences里把默认编译器改为`XeLatex`。
2. 克隆仓库，然后用`xelatex`编译`thesis.tex`。
```
git clone https://github.com/ckpwinters/ZJUthesis_template

cd ZJUthesis_template/

xelatex thesis.tex
```


## 附录：Windows与macOS对部分中文字体的定义
下表只罗列了四种常见字体，主要出现在报纸和文献中。
可以参照TexLive中的`ctex-fontset-windowsnew.def`与`ctex-fontset-mac.def`的设定。

字体 | Windows(7+) | macOS(10.11+)
---|---|---
宋体| SimSun（中易宋体） | STSong（华文宋体）
黑体| SimHei（中易黑体） | STHeiti（华文黑体）
楷体| KaiTi （楷体）     | STKaiti（华文楷体）
仿宋| FangSong （仿宋）  | STFangsong（华文仿宋）

