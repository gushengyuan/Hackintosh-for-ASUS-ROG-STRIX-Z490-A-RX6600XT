| 组件 | 名称                                   |
| ---- | --------------------------------------|
| CPU  | i7 10700K                             |
| 主板  | ASUS ROG STRIX Z490-A                 |
| iGPU | Intel UHD Graphics 630                |
| 机型 | iMac 20,1                              |
| 网卡 | 英特尔® Wi-Fi 6 AX210                   |


## CPU支持
- [x] 支持所有10代核显为UHD630的CPU
- [x] 无核显带F的10代CPU, 有以下免驱独显也可以(但无法使用核显加速)

## 显卡支持
- [x] 支持仅有CPU核显的UHD630显卡
- [x] 支持AMD独显 RX 470/480/570/570X/580/580X/590 系列显卡
- [x] 支持AMD独显 RX 5500/5600/5700/6600/6800/6900 系列显卡(需使用在boot-args中加入agdpmod=pikera)


## BIOS设置
禁用以下选项：
- Fast Boot快速启动
- VT-d
- CSM兼容性支持模块
- CFG LOCK

启用以下选项：
- VT-x
- Above 4G decoding 大于 4G 地址空间解码
- Hyper Threading 处理器超线程
- Execute Disable Bit 执行禁止位
- EHCI/XHCI Hand-off 接手 EHCI/XHCI 控制
- OS type: other types 操作系统类型: 其他

## 参考文档
- https://www.yuque.com/turanfafeng/kb
- https://blog.csdn.net/weixin_39929723/article/details/112146548
