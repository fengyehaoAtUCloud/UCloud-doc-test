{{indexmenu_n>60}}


# VServer的运行状态是指什么？

"运行"是指整个负载均衡的状态，只要后端服务器有一台存活，负载均衡还是运行状态。

后端服务器的状态通过绿色/红色指示灯表示。

需注意的是，后端状态由负载均衡健康检查确定。如果健康检查失败，即使服务器还能ping通，也认为是宕机。

[[https://github.com/UCloudDocs/UCloud-document/issues/3|{{https://static.ucloud.cn/e7fec9d74c744c448d757fad04fe1bcb.png}}]]
