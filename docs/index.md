# Welcome to zzw4257's Notebook

本博客正在施工中，该页面用于记录一些自己记不住的语法

## 部署相关

本页面通过 github actions 生成gh-pages branch并静态部署，因此只需要在第一次用action构建，后续**不需要**。

## markdown扩充语法

from [admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions)

### Admonitions (call-out)

Supported types:`note`,`abstract`,`info`,`tip`,`success`,`question`,`failure`,`warning`,`danger`,`bug`,`example`,`qu`

#### Note

```
!!! [type] ["title"]
[content] 
```

!!! note

这是一个有标题的 `note`

!!! note " "

这是一个没有标题的 `note`，真的丑

!!! node "自定义标题"

这是一个自定义标题的 `note`

!!! example "一个特殊的例子"

!!! tip "一个温馨提示"

!!! warning

!!!

#### Collapsible blocks

如果我们想要将内容折叠则

```
???+ [type] ["title"]
    [tab]folded content
```

???+ note "折叠note"

    你太帅了

???+ tip "折叠tip"

    你太帅了

???+ quote "高尔基名言"

    我是傻逼

### inline block

```
!!! info inline end "右侧的Info"

    Lorem ipsum dolor sit amet, consectetur
    adipiscing elit. Nulla et euismod nulla.
    Curabitur feugiat, tortor non consequat
    finibus, justo purus auctor massa, nec
    semper lorem quam in massa.
```

!!! info inline end "右侧的Info"

    Lorem ipsum dolor sit amet, consectetur
    adipiscing elit. Nulla et euismod nulla.
    Curabitur feugiat, tortor non consequat
    finibus, justo purus auctor massa, nec
    semper lorem quam in massa.

### 自定义环节

参考[官网](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#customization "官网自定义教程")

???+ zzw
    哈哈哈哈
