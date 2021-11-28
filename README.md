# 郑州大学 Beamer 主题集合

本项目是在前人的基础上编写的展示用 Beamer 主题集合。目前提供以下几种主题：

| 主题名称             | 作者                            | 封面截图                                     | 内页截图                                     |
| ---------------- | ---------------------------------- | ---------------------------------------- | ---------------------------------------- |
| `ZZU(改编自HFUT)`             | [孙晓](https://github.com/sxhfut/)   | ![zzu-front](https://github.com/ZZUTUG/ZZU-Beamer/blob/images/ZZU_1_font.png) | ![zzu-inner](https://github.com/ZZUTUG/ZZU-Beamer/blob/images/ZZU_1_inner.png) |

可以在`example.tex`中的`\usetheme{...}`中填入主题名进行调整主题的调整。默认采用16:9比例，可以删除`\documentclass[aspectratio=169]{beamer}`中的`[aspectratio=169]`切换回4:3比例。

对于 Beamer 的中文缩进和段间距问题，可使用以下的代码片段进行修正。建议仅在需要的地方使用，不要直接作用于全局。

```latex
\setlength{\parskip}{6pt}
\setlength{\parindent}{2em}
```
## 本人是业余玩家，以后尽可能多更新。欢迎ZZU的同学[加入](mailto:boss.bingo0e@icloud.com)！
## 更多资料

- [Beamer 用户手册](https://github.com/latexstudio/LaTeXPackages-CN/raw/master/beamer/beamer%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C%EF%BC%88V3.24%EF%BC%89%E4%B8%AD%E8%AF%91%E7%89%88.pdf)

