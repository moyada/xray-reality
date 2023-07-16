## 安装/更新方式

支持配置方式

- VLESS + TCP + XTLS / TLS  + REALITY

```
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/moyada/xray-reality/master/install.sh" && chmod +x install.sh && bash install.sh
```


### 注意事项
* 如果你不了解脚本中各项设置的具体含义，除域名外，请使用脚本提供的默认值；
* 使用本脚本需要你拥有 Linux 基础及使用经验，了解计算机网络部分知识，计算机基础操作；
* 目前支持 Debian 9+ / Ubuntu 18.04+ / Centos7+ / Oracle Linux 7+；
* 群主仅提供极其有限的支持，如有问题可以询问群友。

### 鸣谢

* 本脚本中 README Project_Xray 项目图片由 Blitzcrank Telegram:@Blitz_crank 提供 在此感谢Blitzcrank
* 本脚本中 MTProxyTLS 基于 https://github.com/sunpma/mtp 二次修改 在此感谢 sunpma；
* 本脚本中 锐速 4 合 1 脚本原项目引用 https://www.94ish.me/1635.html 在此感谢；
* 本脚本中 锐速 4 合 1 脚本修改版项目引用 https://github.com/ylx2016/Linux-NetSpeed 在此感谢 ylx2016；
* 本脚本中 配置文件及部分逻辑参考 https://github.com/jiuqi9997/xray-yes 在此感谢 玖柒；
* 本脚本中 二维码 API 部分参考 https://github.com/mack-a/v2ray-agent  在此感谢 mack-a。

### 启动方式

启动 Xray：`systemctl start xray`

停止 Xray：`systemctl stop xray`

启动 Nginx：`systemctl start nginx`

停止 Nginx：`systemctl stop nginx`

### 相关目录

Web 目录：`/www/xray_web`

Xray 服务端配置：`/usr/local/etc/xray/config.json`

Nginx 目录： `/etc/nginx`

证书文件： `/ssl/xray.key`（私钥）和 `/ssl/xray.crt`（证书公钥）
