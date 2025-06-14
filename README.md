# Bindgen 工具分析

这个仓库包含了关于Bindgen工具的分析文档，主要介绍了Bindgen的工作原理、实现细节以及与其他工具（如cbindgen）的对比。

## 目录结构

```
.
├── README.md
├── blog.md
└── images/
    ├── image.png
    ├── image1.png
    └── image2.png
```

## 内容概述

- 工作背景：介绍Rust和C语言交互中的ABI问题
- 已有工作分析：分析现有工具（如cbindgen）的优缺点
- Bindgen工作流程：详细介绍Bindgen的三个主要阶段
  - Builder阶段
  - Parser阶段
  - Writer阶段
- Opaque对象处理：分析Bindgen如何处理opaque对象
- 结果展示：展示Bindgen生成的各种数据结构的绑定代码
- 未来工作：列出待支持的数据结构和功能

## 图片说明

1. `image.png`: Bindgen工作流程图
2. `image1.png`: 解析过程图
3. `image2.png`: Adjust处理流程图 