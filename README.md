# newifi3-d2-openwrt

> 适用于新三路由器的openwrt固件

 - Release和Actions现在都默认使用coolsnowwolf分支源码：https://github.com/coolsnowwolf/lede
 - openwrt版本：21.02
 - 内核：5.4.x
 - openwrt软件源已默认配置为腾讯云源( `https://mirrors.cloud.tencent.com/` )

## 食用前的重要提示

- 本仓库为 [xfl12345](https://github.com/xfl12345) 个人自用，没有小白新手说明。原仓库地址是 [https://github.com/Jeffery186/newifi3-d2-openwrt](https://github.com/Jeffery186/newifi3-d2-openwrt)
- 默认管理地址为`192.168.10.1`，密码`password`

## dev_xfl 分支：

dev_xfl分支为默认分支，常规使用下载该分支编译的固件即可  

## coolsnowwolf

### 源码

via：`https://github.com/coolsnowwolf/lede`

### 下载

下载Release版或Actions都可以  

#### Release

`https://github.com/xfl12345/newifi3-d2-openwrt/releases`

#### Actions

到`Actions`构建页面 `https://github.com/xfl12345/newifi3-d2-openwrt/actions/workflows/build-openwrt-immortalwrt-b1.yml` 下载，刷入时使用含有`openwrt-ramips-mt7621-d-team_newifi-d2-squashfs-sysupgrade.bin`类似名字的bin固件；

Actions下载页面附带有一同编译的软件包  

下载 `openwrt-ramips-mt7621-d-team_newifi-d2.manifest` 文件可查看固件内核版本和固件所包含的软件包信息，使用文本编辑器如 `Sublime Text` 等都可以打开查看

## 说明：

 **致谢：**

[https://github.com/coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)

## 克隆本项目

由于历史原因，克隆时请加上 `--depth=1` 参数

如：

```shell
git clone --depth=1 https://github.com/xfl12345/newifi3-d2-openwrt.git
```

or:

```shell
git clone --depth=1 git@github.com:xfl12345/newifi3-d2-openwrt.git
```

## 更新日志：

#### 2022.1.1

- 增加U盘自动挂载支持
- 增加kmod-tun内核模块

#### 2021.10.19

- openwrt源码改用immortalwrt

#### 2021年7月17日

- 添加nfs内核