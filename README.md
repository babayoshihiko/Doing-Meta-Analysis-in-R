# Doing Meta-Analysis with R: A Hands-On Guide

---

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/MathiasHarrer.svg?style=social&label=MathiasHarrer)](https://twitter.com/MathiasHarrer)
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/pimcuijpers.svg?style=social&label=pimcuijpers)](https://twitter.com/pimcuijpers)
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/pimcuijpers.svg?style=social&label=Toshi_FRKW)](https://twitter.com/Toshi_FRKW)
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/DDEbert.svg?style=social&label=DDEbert)](https://twitter.com/DDEbert)



<a href="https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/" target="_blank"><img src="images/cover.png" width="250" align="right" alt="" class="cover" /></a> Welcome to the GitHub repository of <a href="https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/" target="_blank"><strong>"Doing Meta-Analysis with R: A Hands-On Guide"</strong></a>.

本書は、 _R_ でメタアナリシスを行う方法について、わかりやすく紹介するものである。メタアナリシスの基本的な手順として、結果指標のプーリング、フォレストプロット、異質性解析、サブグループ分析、メタ回帰、出版バイアスの制御方法、バイアスリスク評価、プロッティングツールなどを網羅している。

また、ネットワークメタ解析、多段/3段メタ解析、ベイズメタ解析アプローチ、SEMメタ解析など、高度でありながら関連性の高いトピックも扱う。

本書で扱うプログラミングや統計的背景は、**非専門家レベル**にとどめる。本書の**印刷版**は、 [Chapman & Hall/CRC Press](https://www.routledge.com/Doing-Meta-Analysis-with-R-A-Hands-On-Guide/Harrer-Cuijpers-Furukawa-Ebert/p/book/9780367610074) (Taylor & Francis) から出版されている（訳注: 英語による原著）。


<br></br>

## オープンソースレポジトリ

---

The book has been built using [**{rmarkdown}**](https://rmarkdown.rstudio.com/docs/) and [**{bookdown}**](https://bookdown.org/). Formulas are rendered using [MathJax](http://docs.mathjax.org/en/latest/index.html). All materials and source code we used to compile the guide can be found in this repository. You are free to fork, share and reuse contents. However, the repository is intended to be mainly "read-only"; PRs will generally not be considered (see section below & [preface](https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/preface.html#contact-us) of the book for ways to contact us).   
この本は、[**{rmarkdown}**](https://rmarkdown.rstudio.com/docs/) と [**{bookdown}**](https://bookdown.org/) を使って構築している。数式は [MathJax](http://docs.mathjax.org/en/latest/index.html) を使ってレンダリングしている。このガイドをコンパイルするために使用したすべての資料とソースコードは、このリポジトリで見つけることができる。内容をフォークしたり、共有したり、再利用するのは自由である。ただし、このリポジトリは主に「読むだけ」を目的としており、PRは基本的に考慮されていない（連絡方法については、以下のセクションと書籍の [preface](https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/preface.html#contact-us) を参照していただきたい）。  



<br></br>

## 貢献 

---

本ガイドはオープンソースプロジェクトであり、本ガイドのいくつかのセクションで追加コンテンツを提供してくれた専門貢献者に特別な感謝を捧げる。

* [**Luke A. McGuinness**](https://twitter.com/mcguinlu), University of Bristol: Chapter 15, Risk of Bias Plots.

このガイドに貢献したい？**Mathias** (mathias.harrer@fau.de) にメールを送り、あなたの提案する追加事項を伝えよう。

<br></br>

## 本ガイドへの引用

---

以下のように引用していただきたい。

```{block, type='boxempty'}
Harrer, M., Cuijpers, P., Furukawa, T.A., & Ebert, D.D. (2021). _Doing Meta-Analysis with R: A Hands-On Guide_. Boca Raton, FL and London: Chapmann & Hall/CRC Press. ISBN 978-0-367-61007-4.
```

Download the reference as [BibTeX](https://www.protectlab.org/meta-analysis-in-r/data/citation.bib) or [.ris](https://www.protectlab.org/meta-analysis-in-r/data/citation.ris).

<br></br>


## パッケージの引用

---

このガイドでは、様々な _R_ パッケージを紹介し、使用している。これらのパッケージを誰でも無料で使えるのは、世界中の専門家が膨大な時間と労力を費やして、通常は無報酬で開発してきたからである。本書で紹介されているパッケージをメタ分析に使用する場合は、報告書にも引用されることを強く推奨する。

このガイドでは、新しいパッケージが紹介されるたびに、それを引用するためのリファレンスも提供している。また、`citation("package")` を実行することで、好ましい参考文献を取得することもできる。みなさんに感謝する。


<br></br>

## 日本語版の翻訳

`MathiasHarrer/Doing-Meta-Analysis-in-R` より、フォークした (2022年5月17日) 。日本語版は、branch を `master` から `ja` に変更する。

RStudio でビルドする際は、`Build` タブから `Build Book` &gt; `bookdown::bs4_book` を選択する。`gitbook` と `pdf_book` には対応していない。