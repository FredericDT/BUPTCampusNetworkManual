# 西土城校区 BUPT-mobile

ESSID: BUPT-mobile
## 简介

本 ESSID 主要提供支持 WPA2-Enterprise 安全标准的无线终端接入，用户通过 EAP 认证后，即可利用本接入服务实现满足下行上网需求。
## 接入方法

### 简介

1. 信任证书"BUPT Local Server Certificate"
   - [PEM 在这里](./Wireless/XTC-BUPT-mobile-assets/BUPT-Local-Server-Certificate.crt)
2. 键入用户名（学工号）及凭证
3. 接入
### Android

#### 简介

1. 下载证书"BUPT Local Server Certificate"。
2. 在“设置”-“安全”-“高级”（或称“更多安全设置”）-“加密与凭据”-“安装证书”（或称“从存储设备安装”）-“WLAN 证书”安装步骤 1 中下载的证书，“为此证书命名”可以填写“BUPT Local Server Certificate”。
3. 在“设置”-“网络和互联网”-“WLAN”-连接 "BUPT-mobile"-“CA 证书”-选择步骤 2 中安装的“BUPT Local Server Certificate”；在“阶段 2 验证”选择“MSCHAPV2”；在“域名”填写“BUPT Local Server Certificate”；在“身份”输入学工号；“密码”为校园网账号密码。
4. 点击“连接”。

#### 逐步指引

1. 下载证书"BUPT Local Server Certificate"。

2. 在“设置”-“安全”-“高级”（或称“更多安全设置”）-“加密与凭据”-“安装证书”（或称“从存储设备安装”）-“WLAN 证书”安装步骤 1 中下载的证书，“为此证书命名”可以填写“BUPT Local Server Certificate”。
    ![](./Wireless/XTC-BUPT-mobile-assets/Android-guide-figure-1.png)

3. 在“设置”-“网络和互联网”-“WLAN”-连接 "BUPT-mobile"-“CA 证书”-选择步骤 2 中安装的“BUPT Local Server Certificate”；在“阶段 2 验证”选择“MSCHAPV2”；在“域名”填写“BUPT Local Server Certificate”；在“身份”输入学工号；“密码”为校园网账号密码。
    ![](./Wireless/XTC-BUPT-mobile-assets/Android-guide-figure-2.png)

4. 点击“连接”。
### iOS

TBD
### Windows 10

TBD

### macOS

TBD
## 技术方案

TBD

## 拓扑关系

