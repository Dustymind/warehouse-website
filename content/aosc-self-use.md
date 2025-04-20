---
title: "AOSC 自用软件包"
date: 2025-04-17T08:36:29+08:00
draft: false
---

适用于 [AOSC OS](https://aosc.io) 的软件包（编译脚本及二进制包），[仓库](https://github.com/Dustymind/warehouse/tree/main/aosc-self-use)结构与[aosc-os-abbs](https://github.com/AOSC-Dev/aosc-os-abbs)相同。  
仓库内软件包因为~~懒得维护~~没得时间维护，暂不向主源提交。如需取用请自行编译或前往 [releases](https://github.com/Dustymind/warehouse/releases) 下载。

编译/安装顺序见各软件包（组）说明。  
具体的编译步骤请参考[AOSC Wiki](https://wiki.aosc.io/zh/developer/packaging/basics/)

## libTAS

See also [libTAS](https://github.com/clementgallet/libTAS).

编译/安装顺序：
```
xcb-util+32 xcb-util-keysyms+32 libtas
```
