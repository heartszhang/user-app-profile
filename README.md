# 移动用户装机列表



## 数据来源

- 手机用户开放给各应用的应用列表权限
- 由各应用收集而成
- 收集自互联网

## 典型用户

- 正常`Android`手机用户
- 某些各种用途的真实手机设备
- 某些各种用途的虚拟机设备
- 数据中没有过滤系统应用
- 没有过滤各种`Service` 和 `Provider`

## 数据格式

### `user-apps-uncensored.csv`

| brand | manu       | uid    | osver    | installed    | app_counts   |
| ----- | ---------- | ------ | -------- | ------------ | ------------ |
| 品牌  | 手机制造商 | 用户ID | 系统版本 | 装机应用列表 | 装机应用个数 |

```csv
gn151,gionee,188436,4.4.2,天气|userdictionary|drm保护内容存储|keyguardtestactivity|android系统|浏览器|手机管家|网络位置|sim卡应用|声音和振动|输入设备|号码归属地|时钟|下载管理程序|云端备份|应用包访问权限帮助程序|hotlinesprovider|系统备份|电话/信息存储|amigo设置存储|系统管家|wifi万能钥匙|联系人存储|定时开关机|下载管理|媒体存储|信息|随变桌面|日历|日历存储|搜索应用程序提供商|语音引擎|gioneepushengine|系统用户界面|联系人|wlan|游戏大厅|蓝牙|amigo系统服务|cellconnectionservice|一体化位置信息|incallui|amigo账号|搜狗输入法|gn_schairplane,45
```

### `apps-full.csv`

| app            | count |
| -------------- | ----- |
| 天气           | 55623 |
| userdictionary | 83182 |
```csv
keyguardtestactivity,35343
android系统,178746
```

