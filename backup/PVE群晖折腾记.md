安装详见[pve8.1安装群晖教程](https://www.freehelpme.com/pve8-1/)，B站的原视频跳转了，可以到Youtube上观看，几个小坑注意跳过。

1. RR引导要选rr_4G.img 
引导盘要用4g版本，教程中的引导盘是1G版，SA6400 7.2DSM有410M，下载分区空间不够无法编译引导程序。
2. 在PVE中加载RR引导盘用虚拟SATA驱动，
用SCSI驱动，DSM安装到55%、56%会出错。
![无法安装DSM](https://github.com/waqian/blog/assets/137795786/c431b082-66f2-46de-baff-ad3b485d7f28)
