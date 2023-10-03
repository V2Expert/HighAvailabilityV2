# 高可用翻墙梯子

## 目的

- 在大部分时间不会被墙
- 即使被墙了也能在1小时内恢复

## 原理

高可用梯子节点维护非常频繁，因为需要及时探测是否被墙，然后立刻更换没被墙的IP。

## 价格

由于人力成本大以及购买IP池，甚至购买ISP专线，因此价格比较高

## 使用方法

首先配置你本地DNS服务器为```4.2.2.1```以防污染，然后刷新DNS缓存：

- Windows: cmd执行```ipconfig /flushdns```
- Linux: bash执行```sudo systemctl restart systemd-resolved```或```sudo systemctl restart network```
- macOS: bash执行```sudo killall -HUP mDNSResponder```
- iOS/Android: 重启

然后[购买订阅](https://myrealfree.com)即可。当你发现某个节点延迟变大或者无法使用时，刷新订阅即可（订阅URL不变）。
