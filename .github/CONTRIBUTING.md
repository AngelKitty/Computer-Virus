CONTRIBUTING to Computer-Virus
---

> 目前网上很缺乏关于如何去开发病毒和研究病毒的一些素材和学习资料。我希望的是大家来共同维护着一个开源的学习平台。在你从本项目中获取某个有用的病毒资料时，相对的，我希望你能向 `Computer-Virus` 贡献一个病毒样例。

## 向 Computer-Virus 贡献前需要注意的几个点：

- [接受何种形式的贡献](#cc)
- [目录结构](#dir)
- [病毒文件说明](#files)
- [Commit 规范](#commit)
- [贡献流程](#howto)
- [联系方式](#url)

### <a name="cc"></a>接受何种形式的贡献

* 新增环境及完善资料
    * 病毒源程序
    * 病毒详细说明
    * 病毒运行程序
    * 病毒查杀工具
* 原有程序 Bug 修复
* 逆向分析病毒报告

### <a name="dir"></a>Computer-Virus 目录结构

`/组件首字母/组件名/该组件的目录下的维一编号/`

> 一律采取小写
>
> 唯一编号使用阿拉伯数字

```
.
├── README.md
├── base 组件基础
├── 组件首字母
│   ├── README.md(组件列表)
│   └── 组件名
│       ├── README.md(组件病毒文件列表)
│       ├── 唯一编号
│       └── 唯一编号
├── b
│   ├── README.md
│   └── bash
│       ├── README.md
│       ├── 1
│       └── 2
└── s
    ├── README.md
    └── struts2
        ├── README.md
        └── 1
```

### <a name="files"></a>病毒样例文件说明

```
.
├── README.md    病毒说明(需要指明病毒详细信息及开发思路、来源、分析思路(包括但不限于特征行为分析))
├── figure       存放README.md中涉及的图片信息
├── sources      存放病毒源程序和运行程序
├── tools        存放病毒的查杀工具
```

### <a name="commit"></a>Commit 规范

Commit 分为标题和主体两部分，标题要求必须要简洁明了。对标题的详细补充在主体中体现，如果标题已经充分表达出提交者的意思，主体可省略。

```
(操作 文件类型: 病毒的组件名) 插件名或组件版本号
<空行>
详细的说明
```

* 操作:
 * Add    添加
 * Update 更新
 * Fix    修补 Bug
 * Delete 删除

* 文件类型
 * Base   组件基础

### <a name="howto"></a>贡献流程

* Step1. fork 本仓库到你自己的仓库

* Step2. clone 自己的仓库到本地

* Step3. 本地添加环境或修改文档，然后推至远端自己的仓库

* Step4. 发起 Pull Request

### <a name="urls"></a>联系方式

* 博客园：https://www.cnblogs.com/ECJTUACM-873284962/
* Gmail邮箱：<angelkitty6698@gmail.com>