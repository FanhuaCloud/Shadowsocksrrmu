# Shadowsocksrrmu
逗比ssrmu.sh魔改版

#### 下载安装
------------
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/FanhuaCloud/Shadowsocksrrmu/master/ssrmu.sh && chmod +x ssrmu.sh && bash ssrmu.sh
```
#### 魔改内容
------------
- 更改服务端为ShadowsocksRR服务端
- 新增auth_chain_c/d/e/f协议,详询https://github.com/shadowsocksrr/shadowsocksr-csharp/releases
- 新增xsalsa20,xchacha20加密，详询https://github.com/shadowsocksrr/shadowsocksr-csharp/releases
- 去掉原版脚本更新检测
- 已更新：支持更新服务端
- 新版更新：不再修改iptables，请手动配置

#### 推荐服务器
------------
- 打个广告，搬瓦工双11特别款，仅售$29.88一年，拿来做梯子速度不错：
https://blog.craftyun.cn/post/171.html

#### 官方说明
------------
- 脚本说明: ShadowsocksR 一键安装/管理脚本，支持单端口/多端口切换和管理
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/ss-jc42/
- 项目地址: https://github.com/shadowsocksr/shadowsocksr/tree/manyuser

##### 脚本特点:
目前网上的各个ShadowsocksR脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

- 支持 限制 用户速度
- 支持 限制 端口设备数
- 支持 显示 当前连接IP
- 支持 显示 SS/SSR连接+二维码
- 支持 切换管理 单/多端口
- 支持 一键安装 锐速
- 支持 一键安装 BBR
- 支持 一键封禁 垃圾邮件(SMAP)/BT/PT

#### 版权说明

------------

版权归**ToyoDAdoubi**所有，原项目地址：https://github.com/ToyoDAdoubi/doubi
如有版权问题可以联系我，我将立刻删除该脚本

