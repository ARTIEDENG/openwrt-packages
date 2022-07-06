基于liuran001 /openwrt-packages项目添加常用IPTV插件

使用方式参考liuran001的三种使用方法：
`还是建议按需取用，不然碰到依赖问题不太好解决`
1. 先cd进package目录，然后执行
```bash
 git clone https://github.com/liuran001/openwrt-packages
```
2. 或者添加下面代码到feeds.conf.default文件
```bash
 src-git liuran001_packages https://github.com/liuran001/openwrt-packages
```
3. 先cd进package目录，然后执行
```bash
 svn co https://github.com/liuran001/openwrt-packages/branches/packages
```

