💖💖（不要同步复刻）


# serv00 上的一些应用，包括 argo+vmess/vmess+ws/hy2/socks5/mtproto/alist等部署、保号、进程防杀、消息推送

## 前置工作

1. 你需要有一个 serv00 帐号
2. 无需使用面板，安装 serv00-play 后，按 13 即可
3. 密：fkjyyds666
4. 选择------（13) 设置中国时区及前置工作---（1) 安装/更新serv00-play项目------（7) 配置sing-box 
## 安装说明

```s
bash <(curl -Ls https://raw.githubusercontent.com/frankiejun/serv00-play/main/start.sh)
```
```s
bash <(curl -Ls https://raw.githubusercontent.com/FFLLZZ/serv00-play/main/start.sh)
```

## 变量说明

| 变量名              | 示例   | 备注                                     |
| ------------------- | ------ | ---------------------------------------- |
| HOSTS_JSON          | 见示例 | 可存放 n 个服务器信息                    |
| TELEGRAM_TOKEN      | 略     | telegram 机器人的 token ~~               |
| TELEGRAM_USERID     | 略     | 待通知的 teltegram 用户 ID               |
| SENDTYPE            | 3      | 选择推送方式，1.Telegram, 2.微信, 3.都有 |

PS. 保进程逻辑已挪到 serv00 上做，actions 只做保号，降低访问频率. github 上只需配置 HOSTS_JSON

## 消息推送

支持向 Telegram 和微信用户发送通知

关于如何配置 Telegram 以实现消息推送，可以看 [这个视频](https://www.youtube.com/watch?v=l8fPnMfq86c&t=3s)

关于微信的配置，目前使用第三方平台提供的功能，可以到 [这里](https://sct.ftqq.com/r/13223) 注册并登录 server 酱，取得 sendKey

## HOSTS_JSON 的配置实例

```js
 {
   "info": [
    {
      "host": "s2.serv00.com",
      "username": "kkk",
      "port": 22,
      "password": "fdsafjijgn"
    },
    {
      "host": "s2.serv00.com",
      "username": "bbb",
      "port": 22,
      "password": "fafwwwwazcs"
    }
  ]
}
```

## 安装说明视频

安装使用说明及使用密码可以看[这里](https://youtu.be/bpYV8r85F-8)

临时隧道已失效，请使用固定隧道名，[如何申请固定隧道名](https://youtu.be/KyMvtWknu-k)



## 项目鸣谢

[qwer-search](https://github.com/qwer-search) 、[k0baya](https://github.com/k0baya) 、[eooce](https://github.com/eooce)

## 免责声明

本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责。
