# 高可用翻墙梯子

## 目的

- 在大部分时间不会被墙
- 即使被墙了也能在1小时内恢复

## 原理

梯子节点维护非常频繁，需要及时探测是否被墙，然后立刻更换没被墙的IP。

## 价格

由于这类梯子人力成本比较大及购买IP池，甚至购买ISP专线，因此价格比较高。但是除了支持常规的支付宝/微信外，还能支持USDT币安支付。

## 使用方法

首先配置你本地DNS服务器为```4.2.2.1```以防污染，然后刷新DNS缓存：

- Windows: cmd执行```ipconfig /flushdns```
- Linux: bash执行```sudo systemctl restart systemd-resolved```或```sudo systemctl restart network```
- macOS: bash执行```sudo killall -HUP mDNSResponder```
- iOS/Android: 重启

然后[购买订阅](https://myrealfree.com)即可。当你发现某个节点延迟变大或者无法使用时，刷新订阅即可（订阅URL不变）。

## 注意事项

- 别在跑梯子的设备上装流氓软件。常见流氓软件：360、腾讯、百度。。。
- 别挂着梯子逛国内网站，不然和流氓软件一个道理
- 用完梯子及时断开连接
