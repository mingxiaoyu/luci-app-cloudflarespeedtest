# luci-app-cloudflarespeedtest

[![Upload Release Asset](https://github.com/mingxiaoyu/luci-app-cloudflarespeedtest/actions/workflows/build.yml/badge.svg)](https://github.com/mingxiaoyu/luci-app-cloudflarespeedtest/actions/workflows/build.yml)

## Cloudflare speed test for LuCI / 适用于 LuCI 的 loudflare speed test插件
- 一个用于定时执行Cloudflare IP 速度测试的插件。集成SSR+和PASSWALL替换IP
- [Download / 下载 ipk](https://github.com/mingxiaoyu/luci-app-cloudflarespeedtest/releases)

## Depends / 依赖
- [openwrt-cdnspeedtest](https://github.com/immortalwrt-collections/openwrt-cdnspeedtest)

## Compile / 编译
```bash

#compile package only
make package/luci-app-cloudflarespeedtest/compile v=99

#compile
make menuconfig
#choose LuCI ---> 3. Applications  ---> <*> luci-app-cloudflarespeedtest..... for LuCI ----> save
make V=99
```

 ![overview](https://github.com/mingxiaoyu/luci-app-cloudflarespeedtest/blob/main/doc/overview.jpeg?raw=true)
 
  # 感激 
 [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest)
