# 美国

## inmotionhosting - 美国

基本情况

* 机型: 8C/16G/260G SSD
* 价格: $155/年 (黑五打折价格)
* 带宽: 1G CN2 共享，无限流量，测试中
* 路由: 联通去程 CN2 GT，回程CN2 GT

性能测试

1. [CPU](https://browser.geekbench.com/v6/cpu/8999204)

## dmit.io - 美国

基本情况

* 机型: PVM.LAX.Pro.Pocket，1C/2G/40G SSD
* 价格: $15
* 带宽: 4G CN2 GIA 共享，1500GB流量，全天测试基本都10Mbps偶尔速度能到120Mbps
* 路由: 联通去程 CN2 GT，回程CN2 GIA

## rfchost - 香港

基本情况

* 机型: HKG02 CN2，1C/0.5G/8G SSD
* 价格: $12 (优惠后)
* 带宽: 100M 共享，偶尔可以打满，500GB流量
* 路由: CN2

缺点

1. 工单回复很慢
2. 机器配置非常低，尤其是硬盘很小

优点

1. 虚拟化比较新，有SSE4_1，比其他亚洲供应商强

## cubecloud - 香港

基本情况

* 机型: HK CN2 PRO，1C/1G/15G SSD
* 价格: 67 RMB (节假日经常有优惠)
* 带宽: 50M CN2 共享，400G流量，实际最多能用到20M
* 路由: 联通去程AS4837 + AS10099，回程59.43，是CN2 GIA线路

优点

1. 有IPv6地址

缺点

1. 不能开IPSec VPN，NTP、邮件服务出入端口全封
2. 服务态度差，香港经常有稳定性问题，SLA保证不了
3. 不能用Paypal支付，或者价格过高

## gigsgigscloud - 香港

基本情况

* 机型: HK Premium V1，1C/1G/20G SSD
* 价格: $22
* 带宽: 10M CN2，100GB流量
* 路由: CN2

缺点

1. 香港线路在夜间比日本稳定太多了，软银线路连续下载10秒以上，速度下降到100KB
2. 基于QEMU、无KVM，CPU很差，无论多少虚拟核都没有意义

## gigsgigscloud - 美国

基本情况

* 机型: US LAX Premium V1，1C/0.5G/20G SSD
* 价格: $12
* 带宽: 1G CN2，1TB流量；夜间测试下载速度能到1MB左右，白天能到5MB，不稳定
* 路由: 联通去程AS9929 + AS10099，回程59.43
