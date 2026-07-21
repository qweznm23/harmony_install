# MyWidget HarmonyOS Install

GitHub Pages 分发地址：

```text
https://qweznm23.github.io/harmony_install/
```

安装 Deeplink：

```text
store://enterprise/manifest?url=https%3A%2F%2Fmywidget.oss-cn-beijing.aliyuncs.com%2Fmanifest-v3-oss-release.json5
```

安装清单、图标和 HAP 托管在阿里云 OSS，三个对象均为匿名公共读：

```text
https://mywidget.oss-cn-beijing.aliyuncs.com/manifest-v3-oss-release.json5
https://mywidget.oss-cn-beijing.aliyuncs.com/icon.png
https://mywidget.oss-cn-beijing.aliyuncs.com/MyWidget-HarmonyOS-release-2.0.7-v9-20260721-1057.hap
```

`manifest-v3-oss-source.json5` 是待签名源文件，`manifest-v3-oss-release.json5` 是使用应用签名证书生成并通过官方工具验签的发布清单。

## 当前包

```text
bundleName: me.xdd.widget
versionName: 2.0.0
versionCode: 2
buildMode: release
minAPIVersion: 6.0.2(22)
targetAPIVersion: 6.0.2(22)
packageHash: DD3808E7171B7D19781F805D17D30D2E2831D358D11FEE9D27CC09BFC1E153C7
```

真机安装前需要先卸载旧版，因为旧包曾使用 `versionCode: 1000000`。

当前 HAP 最低要求 HarmonyOS `6.0.2(22)`，分发清单中的 API 版本必须与 HAP 内 `module.json` 保持一致。







