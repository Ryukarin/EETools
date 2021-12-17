# EETools

## 介绍

此项目有两个脚本，分贝是对 EmuELEC 的核心系统文件 `kernel.img`、`SYSTEM` 的修改脚本。

- `kernel.sh`
- `system.sh`

## 使用

下载脚本到本地，然后执行脚本，按照提示操作即可。

`bash kernel.sh`

`bash system.sh`

## 说明

将镜像文件 `EmuELEC-xxx.img` 烧录到U盘或TF卡之后，会看到移动设备有些文件，其中以下三个较为重要。

- `dtb.img`
- `kernel.img`
- `SYSTEM`

`dtb.img`：可以理解为根据你的机器硬件配置，启动需要加载对应的驱动程序，
Device Tree是一种描述硬件的数据结构，用于ARM Linux。
Device Tree由一系列被命名的结点（node）和属性（property）组成，而结点本身可包含子结点。
`kernel`：系统启动
`SYSTEM`：系统
