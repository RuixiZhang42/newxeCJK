# newxeCJK

用 XeLaTeX 排版中文，首推使用
[`xeCJK`](https://github.com/CTeX-org/ctex-kit/tree/master/xeCJK)
宏包。`xeCJK` 最早由孙文昌教授开发，历史可以追溯到 2007&nbsp;年。`xeCJK`
功能丰富，对简体中文横排的支持比较完善。但 `xeCJK`
对直排的支持，或者对标点习惯不同的繁体中文、日文排版的支持都很有限。

`newxeCJK` 尝试重构 `xeCJK` 中的 inter-character token
机制，将中文/日文使用的「全形/全角」标点符号细分为
5&nbsp;类，并试图同时支持简中、繁中、日文的横排与直排。

目前 `newxeCJK` 处于研发阶段，不自动检测 XeTeX
引擎的版本是否最新，也不考虑向后兼容 `xeCJK`。希望
`newxeCJK` 提供的思路能在不久的将来成为 `xeCJK` 的一部分。

## Copyright and License

    Copyright 2020 Ruixi Zhang <ruixizhang42@gmail.com>
    
    This work may be distributed and/or modified under the
    conditions of the LaTeX Project Public License, either version 1.3c
    of this license or (at your option) any later version.
    The latest version of this license is in
       https://www.latex-project.org/lppl.txt
    and version 1.3c or later is part of all distributions of LaTeX
    version 2005/12/01 or later.
    
    This work has the LPPL maintenance status `maintained'.
    
    The Current Maintainer of this work is Ruixi Zhang.
    
    This work consists of the files newxeCJK.tex,
                                    README.md (this file)