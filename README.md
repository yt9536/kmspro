## 官方网站：https://v0v.bid

---

---

### windows系统一句命令激活

#### 打开 命令提示符（管理员） 运行：slmgr /skms kms.v0v.bid && slmgr /ato

---

---

## Linux系统 自建KMS服务服务器

### 一键安装KMS服务 （Debian/Ubuntu/Mint 等）
```
wget -N --no-check-certificate git.io/k.sh && chmod +x k.sh && bash k.sh debian
```

### 一键安装KMS服务 （CentOS/Redhat/Fedora 等）（如果系统开启了防火墙 须自行开放 1688 端口）
```
wget -N --no-check-certificate git.io/k.sh && chmod +x k.sh && bash k.sh centos
```

### 启动KMS服务
```
bash k.sh start

服务器IP地址既是KMS服务器地址
也可以将域名解析至IP使用（支持IPv6 即AAAA记录）
```

### 关闭KMS服务
```
bash k.sh stop
```

### 添加开机自启动KMS服务
```
bash k.sh auto
```

### 重启KMS服务
```
bash k.sh restart
```

### 查看KMS服务运行状态
```
bash k.sh status
```

### 卸载KMS服务
```
bash k.sh uninstall
```