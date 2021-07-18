
```
luci-app-samba 和 luci-app-samba4 不能同时编译，同时编译会失败

想选择luci-app-samba4，首先在Extra packages ---> 把autosamba取消，在选择插件的那里把luci-app-samba取消，
然后在Network ---> 把 samba36-server取消，最后选择luci-app-samba4，记得顺序别搞错
```
```
luci-app-dockerman 和 luci-app-docker 不能同时编译，同时编译会编译失败

想要编译luci-app-dockerman或者luci-app-docker

首先要在Global build settings ---> Enable IPv6 support in packages (NEW)（选上）
```
```
luci-app-rebootschedule 和 luci-app-autoreboot 不能同时编译，同时编译会编译失败
```
```
luci-app-ddnsto  如果有兼容性问题，安装好固件后执行 `/etc/init.d/ddnsto enable` 命令
```
```
luci-app-advanced  已内置luci-app-fileassistant文件助手，切莫同时编译他们
```

# 请不要Fork此仓库，你Fork后，插件不会自动根据作者更新而更新!!!!!!!!!!!
