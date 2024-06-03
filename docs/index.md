---
statistics: True
---

<h1 align="center">tkintertools</h1>

<p align="center"><img alt="logo" src="https://xiaokang2022.github.io/tkintertools/logo.png" title="Logo" /></p>

<p align="center">
<code>tkintertools</code> 是一个基于 <code>tkinter</code> 的 <code>Canvas</code> 类的 UI 框架
<br/>
<code>tkintertools</code> is a UI framework based on the <code>Canvas</code> class of <code>tkinter</code>
</p>

<p align="center">
<a href="https://github.com/Xiaokang2022/tkintertools/releases"><img alt="Version" src="https://img.shields.io/github/v/release/Xiaokang2022/tkintertools?include_prereleases&logo=github&label=Version" title="Latest Version" /></a>
<a href="https://pypistats.org/packages/tkintertools"><img alt="Downloads" src="https://img.shields.io/pypi/dm/tkintertools?label=Downloads&logo=pypi&logoColor=skyblue" title="Downloads" /></a>
<a href="https://pepy.tech/project/tkintertools"><img alt="Total Downloads" src="https://img.shields.io/pepy/dt/tkintertools?logo=pypi&logoColor=gold&label=Total%20Downloads" title="Total Downloads" /></a>
<a href="https://github.com/Xiaokang2022/tkintertools"><img alt="Size" src="https://img.shields.io/github/languages/code-size/Xiaokang2022/tkintertools?label=Size&logo=github" title="Code Size"/></a>
<br/>
<a href="https://github.com/Xiaokang2022/tkintertools/watchers"><img alt="Watchers" src="https://img.shields.io/github/watchers/Xiaokang2022/tkintertools?label=Watchers&logo=github&style=flat" title="Watchers" /></a>
<a href="https://github.com/Xiaokang2022/tkintertools/forks"><img alt="Forks" src="https://img.shields.io/github/forks/Xiaokang2022/tkintertools?label=Forks&logo=github&style=flat" title="Forks" /></a>
<a href="https://github.com/Xiaokang2022/tkintertools/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/Xiaokang2022/tkintertools?label=Stars&color=gold&logo=github&style=flat" title="Stars" /></a>
<a href="https://github.com/Xiaokang2022/tkintertools/issues"><img alt="Issues" src="https://img.shields.io/github/issues/Xiaokang2022/tkintertools?label=Issues&logo=github" title="Issues" /></a>
<a href="https://github.com/Xiaokang2022/tkintertools/pulls"><img alt="Pull Requests" src="https://img.shields.io/github/issues-pr/Xiaokang2022/tkintertools?label=Pull%20Requests&logo=github" title="Pull Requests" /></a>
<a href="https://github.com/Xiaokang2022/tkintertools/discussions"><img alt="Discussions" src="https://img.shields.io/github/discussions/Xiaokang2022/tkintertools?label=Discussions&logo=github" title="Discussions" /></a>
</p>

<p align="center">
<a href="https://github.com/Xiaokang2022/tkintertools/pulse"><img alt="Insights" src="https://repobeats.axiom.co/api/embed/ab8fae686a5a96f91fa71c40c53c189310924f5e.svg" /></a>
</p>

<p align="center">
    <a href="https://star-history.com/#Xiaokang2022/tkintertools&Date">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Xiaokang2022/tkintertools&type=Date&theme=dark" />
            <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Xiaokang2022/tkintertools&type=Date" />
            <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Xiaokang2022/tkintertools&type=Date" />
        </picture>
    </a>
</p>

📦 Installation - 安装
-----------------------

### ✅ Stable Version - 稳定版本

* 🔖 Version - 最新版本 : `2.6.21`
* 🕓 Release - 发布日期 : 2024-01-01
* ✨ Feature - 更新内容 : [News-2.6.21](./news/2.6.21/News.md)

```sh linenums="0"
pip install tkintertools
```

???+ "Preview - 预览"

    [![Preview UI](./tutorials/images/1.2-2.1-2.png)](https://xiaokang2022.github.io/tkintertools/tutorials/1-2/#21-%E9%AB%98%E5%BA%A6%E5%8F%AF%E9%85%8D%E7%BD%AE%E7%9A%84%E6%8E%A7%E4%BB%B6)

    [![Preview 3D](./tutorials/images/7.3-3.1-2.png)](https://xiaokang2022.github.io/tkintertools/tutorials/7-3/#%E4%B8%89%E9%80%9A%E8%BF%87-after-%E6%96%B9%E6%B3%95%E5%AE%9E%E7%8E%B0%E7%AE%80%E5%8D%95%E5%8A%A8%E7%94%BB)

</details>

### 🔥 Development Version - 开发版本

* 🔖 Version - 最新版本 : `3.0.0.beta2`
* 🕓 Release - 发布日期 : 2024-06-03
* ✨ Feature - 更新内容 : [News-3.0.0b2](./news/3.0.0/News.md)

```sh linenums="0"
pip install tkintertools==3.0.0b2
```

???+ "Preview - 预览"

    * **Demo1 Light Theme**

    ![Light Theme](./news/3.0.0/demo1-light.png)

    * **Demo1 Dark Theme**

    ![Dark Theme](./news/3.0.0/demo1-dark.png)

    * **Demo2 Light Theme**

    ![Light Theme](./news/3.0.0/demo2-light.png)

    * **Demo2 Dark Theme**

    ![Dark Theme](./news/3.0.0/demo2-dark.png)

!!! warning "Warning - 警告"

    `tkt 2.*` has been discontinued, for new features, please use `tkt 3.*`. Also note that `tkt 3.*` is almost completely incompatible with `tkt 2.*`, and porting a project from `tkt 2.*` to `tkt 3.*` can be difficult.  
    `tkt 2.*` 已放弃支持，如需获取新的功能，请使用 `tkt 3.*`。同时请注意，`tkt 3.*` 与 `tkt 2.*` 几乎完全不兼容，将项目从 `tkt 2.*` 移植到 `tkt 3.*` 可能会十分困难。

## 📦 Dependency - 依赖包

### 1️⃣ darkdetect

* 🔖 Version - 版本 : `0.8.0`
* 📑 License - 许可 : BSD 3-Clause
* 🔗 GitHub - 仓库 : [darkdetect](https://github.com/albertosottile/darkdetect)

## 👀 More - 更多

<div class="grid cards" markdown>

-   [📑 **License - 项目许可**](./LICENSE.md)

    ***

    MIT, one of the most permissive open source licenses  
    MIT，最宽松的开源许可之一

-   [📋 **Todo - 待办事项**](./TODO.md)

    ***

    Let's see what the authors have planned  
    看看作者都有些什么计划

-   [📘 **Changelog - 更新日志**](./CHANGELOG.md)

    ***

    Changelog for all versions  
    所有版本的更新日志

-   [📗 **Contribution Guide - 贡献指南**](./CONTRIBUTING.md)

    ***

    Take a look at this before you contribute  
    在贡献之前先瞄一下这个

-   [📕 **Security Policy - 安全策略**](./SECURITY.md)

    ***

    How to deal with security vulnerabilities  
    安全漏洞的处理方法

-   [📙 **Code of Conduct - 行为准则**](./CODE_OF_CONDUCT.md)

    ***

    Something that contributors should know  
    贡献者应该了解的一些东西

</div>

!!! info "Site statistics - 本站统计"

    - 总页面：{{ pages }}
    - 总字（词）数：{{ words }}
    - 总代码行数：{{ codes }}
    - 总访问量：<span id="busuanzi_value_site_pv"><i class="fa fa-spinner fa-spin"></i></span>

<div align="center" markdown>
[⚡快速开始](./tutorials/1-2.md){ .md-button .md-button--primary title="从认识 tkintertools 开始！" }
[<big>:star:{ .heart } 支持本项目</big>](https://github.com/Xiaokang2022/tkintertools/){ .md-button .md-button--primary title="给项目点个 Star 吧，球球了！" }
[✨最新内容](./news/3.0.0/News.md){ .md-button .md-button--primary title="点我了解最近更新的内容！" }
</div>

---

<div align="center">

<img src="https://contrib.rocks/image?repo=Xiaokang2022/tkintertools" alt="contributors" />

</div>
