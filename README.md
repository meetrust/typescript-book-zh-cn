<div align="center">

<sub><b>TS 7.0 · ZH-CN · UNOFFICIAL FORK</b></sub>

# The Concise TypeScript Book <br>简体中文版

**Simplified Chinese edition**

一本简明的 TypeScript 参考书：修订版简体中文 PDF，配中英文 Markdown 书稿。
<br>
*A concise TypeScript reference: a revised Simplified Chinese PDF, with Chinese and English manuscripts in Markdown.*

[![下载 PDF Download](https://img.shields.io/badge/%E4%B8%8B%E8%BD%BD%20PDF%20Download-122%20%E9%A1%B5-ffb347?style=flat-square&labelColor=111723)](downloads/The_Concise_TypeScript_Book_zh-CN.pdf) [![许可证 License](https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF%E8%AF%81%20License-CC%20BY%204.0-7cc8ff?style=flat-square&labelColor=111723)](LICENSE.MD)

[概览 Overview](#概览--overview) · [章节 Chapters](#章节--chapters) · [说明 Notes](#修订说明--fork-notes)

</div>

## 阅读入口 · Start reading

| 版本 Edition | 内容与用途 What you get |
|---|---|
| [修订版 PDF](downloads/The_Concise_TypeScript_Book_zh-CN.pdf)<br><sub>Revised PDF</sub> | 简体中文 · 122 页 · A4 · 0.6 MB，适合离线、连续阅读<br><sub>Simplified Chinese · 122 pages · A4 · 0.6 MB, for offline, cover-to-cover reading</sub> |
| [中文书稿](book/The_Concise_TypeScript_Book_zh-CN.md)<br><sub>Chinese manuscript</sub> | Markdown · 57 章 · 266 个 TypeScript 示例，适合全文搜索和引用<br><sub>Markdown · 57 chapters · 266 TypeScript samples, for full-text search and quoting</sub> |
| [英文书稿](book/The_Concise_TypeScript_Book_en.md)<br><sub>English manuscript</sub> | Markdown · 与上游原文一致，适合中英文对照<br><sub>Markdown · identical to the upstream original, for side-by-side reading</sub> |
| [其他格式](downloads/)<br><sub>Other formats</sub> | 上游 7 种语言的 EPUB 与 PDF，适合电子书阅读器<br><sub>Upstream EPUB and PDF in 7 languages, for e-readers</sub> |

<sub>前三行是同一本书的三种读法，PDF 由修订后的简体中文书稿生成。第四行是上游发布的 14 个文件，未作修改。</sub><br>
<sub>The first three rows are three ways to read the same book; the PDF is built from the revised Simplified Chinese manuscript. The fourth row is upstream's 14 published files, unchanged.</sub>

## 概览 · Overview

本仓库是 [`gibbok/typescript-book`](https://github.com/gibbok/typescript-book) 的非官方个人学习 Fork。原书《The Concise TypeScript Book》由 Simone Poggiali 撰写，免费且开源，用简洁的讲解和大量短示例介绍 TypeScript 7.0，从类型系统一直讲到高级功能。

本 Fork 修正了简体中文书稿中 6 行的文字与排版问题，并据此重新生成了 122 页的 PDF；英文书稿原样保留，便于中英文对照。

This repository is an unofficial personal study fork of [`gibbok/typescript-book`](https://github.com/gibbok/typescript-book). The original book, The Concise TypeScript Book by Simone Poggiali, is free and open source; it covers TypeScript 7.0 with concise explanations and many short examples, from the type system to advanced features.

This fork fixes wording and typesetting problems on 6 lines of the Simplified Chinese manuscript and rebuilds the 122-page PDF from it; the English manuscript is kept as is, for side-by-side reading.

> [!NOTE]
> 本 Fork 的修改未经原作者审核、认可或背书，内容仍可能存在遗漏或错误。需要权威内容和最新更新时，请以[上游仓库](https://github.com/gibbok/typescript-book)为准。
>
> The changes in this fork have not been reviewed, approved or endorsed by the original author, and errors or omissions may remain. For authoritative and up-to-date content, refer to the [upstream repository](https://github.com/gibbok/typescript-book).

| **122** | **57** | **266** | **6** |
|:---:|:---:|:---:|:---:|
| 页 PDF<br><sub>PDF pages</sub> | 章<br><sub>chapters</sub> | 示例<br><sub>samples</sub> | 行修订<br><sub>line revisions</sub> |

## 章节 · Chapters

| 章与主题 Chapter and topics | 示例 Samples |
|---|:---:|
| [TypeScript 简介](book/The_Concise_TypeScript_Book_zh-CN.md#typescript-简介)：什么是 TypeScript、TypeScript 和 JavaScript、代码生成与降级<br><sub>[TypeScript Introduction](book/The_Concise_TypeScript_Book_en.md#typescript-introduction): what TypeScript is, TypeScript and JavaScript, code generation and downleveling</sub> | 10 |
| [探索类型系统](book/The_Concise_TypeScript_Book_zh-CN.md#探索类型系统)：结构类型、类型推断、类型加宽、类型缩小<br><sub>[Exploring the Type System](book/The_Concise_TypeScript_Book_en.md#exploring-the-type-system): structural typing, type inference, type widening, type narrowing</sub> | 52 |
| [枚举](book/The_Concise_TypeScript_Book_zh-CN.md#枚举)：数字枚举、字符串枚举、常量枚举、反向映射<br><sub>[Enums](book/The_Concise_TypeScript_Book_en.md#enums): numeric, string and constant enums, reverse mapping</sub> | 11 |
| [Class](book/The_Concise_TypeScript_Book_zh-CN.md#class)：构造函数、访问修饰符、抽象类、装饰器、继承等<br><sub>[Class](book/The_Concise_TypeScript_Book_en.md#class): constructors, access modifiers, abstract classes, decorators, inheritance and more</sub> | 25 |
| [类型操作](book/The_Concise_TypeScript_Book_zh-CN.md#类型操作)：从类型创建类型、索引访问类型、内置工具类型<br><sub>[Type Manipulation](book/The_Concise_TypeScript_Book_en.md#type-manipulation): creating types from types, indexed access types, built-in utility types</sub> | 29 |
| [其他](book/The_Concise_TypeScript_Book_zh-CN.md#其他)：异步语言特性、迭代器和生成器、ES6 模块、satisfies 操作符等，共 33 个主题<br><sub>[Others](book/The_Concise_TypeScript_Book_en.md#others): asynchronous features, iterators and generators, ES6 modules, the satisfies operator and more: 33 topics</sub> | 46 |
| 其余 51 章：包括原始类型、缩小范围、对象类型、联合类型、条件类型和泛型<br><sub>The other 51 chapters include primitive types, narrowing, object types, union types, conditional types and generics</sub> | 93 |

<sub>表中列出示例不少于 10 个的六章，按书中顺序排列；各行示例数相加为 266。完整目录见[简体中文书稿的“目录”一节](book/The_Concise_TypeScript_Book_zh-CN.md#目录)。</sub><br>
<sub>The table lists the six chapters with at least 10 samples, in book order; the rows add up to 266. For the full list, see the [table of contents in the English manuscript](book/The_Concise_TypeScript_Book_en.md#table-of-contents).</sub>

## 项目结构 · Structure

```text
book/*_zh-CN.md             简体中文书稿 · Simplified Chinese manuscript
book/*_en.md                英文书稿 · English manuscript
downloads/*_zh-CN.pdf       修订版简体中文 PDF · revised Simplified Chinese PDF
downloads/typescript-book*  上游 7 种语言的 EPUB 与 PDF · upstream EPUB and PDF in 7 languages
README-bg_BG.md ...         上游其他 5 种语言的书稿 · upstream manuscripts in 5 other languages
tools/                      校验与构建脚本 · check and build scripts
website/                    上游网站源码 · upstream website source
```

## 修订说明 · Fork notes

* 本 Fork 同步至上游提交 [`62c7acc`](https://github.com/gibbok/typescript-book/commit/62c7acce7acc6fe0673a60b7719e7a57fe9f3c74)（2026-07-22）；英文书稿与该提交的 `README.md` 完全一致。<br><sub>The fork is synced to upstream commit [62c7acc](https://github.com/gibbok/typescript-book/commit/62c7acce7acc6fe0673a60b7719e7a57fe9f3c74) (2026-07-22); the English manuscript is identical to upstream's README.md at that commit.</sub>
* 简体中文书稿相对该提交的 `README-zh_CN.md` 修订了 6 行，涉及标点、空格、多余字符和语序；PDF 由修订后的书稿生成。<br><sub>The Simplified Chinese manuscript revises 6 lines of upstream's README-zh_CN.md at that commit: punctuation, spacing, stray characters and word order. The PDF is built from the revised manuscript.</sub>
* 修订过程使用 ChatGPT Work 辅助校对和整理；它不是本书的作者、译者或版权所有者。<br><sub>ChatGPT Work assisted with proofreading and tidying; it is not an author, translator or copyright holder of the book.</sub>
* 数据核对于 2026-11-15：页数取自 PDF 元数据，章数和示例数按书稿的二级标题与 TypeScript 代码块统计，不含书稿开头的支持、翻译、下载和目录四节。<br><sub>Data checked on 2026-11-15: the page count comes from the PDF metadata; chapters and samples are counted from the manuscript's second-level headings and TypeScript code blocks, leaving out its four opening sections (support, translations, downloads, table of contents).</sub>

## 许可证 · License

原书和主要内容由 Simone Poggiali 创作，上游仓库是 [`gibbok/typescript-book`](https://github.com/gibbok/typescript-book)，另有[上游在线版](https://gibbok.github.io/typescript-book/)。本 Fork 不主张对原书内容拥有原创版权。

本仓库沿用上游的 [CC BY 4.0 许可证](LICENSE.MD)，原作者署名和版权声明保持不变。“个人学习”只是用途说明，不是新增的法律限制。

The book and its main content are the work of Simone Poggiali. The upstream repository is [`gibbok/typescript-book`](https://github.com/gibbok/typescript-book), which also publishes an [online edition](https://gibbok.github.io/typescript-book/). This fork claims no original copyright in the book's content.

This repository keeps upstream's [CC BY 4.0 license](LICENSE.MD), with the author attribution and copyright notice unchanged. "Personal study" describes how the fork is used; it is not an additional legal restriction.
