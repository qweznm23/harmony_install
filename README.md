# MyWidget HarmonyOS Install

GitHub Pages 分发地址：

```text
https://qweznm23.github.io/harmony_install/
```

安装 Deeplink：

```text
store://enterprise/manifest?url=https%3A%2F%2Fqweznm23.github.io%2Fharmony_install%2Fmanifest-v2-release.json5
```

## 当前包

```text
bundleName: me.xdd.widget
versionName: 2.0.0
versionCode: 2
buildMode: release
minAPIVersion: 6.0.2(22)
targetAPIVersion: 6.0.2(22)
packageHash: 8B450C39D89F27CE801CD138AE60F1243C2B6E271BE012A84C1082171A10658F
```

真机安装前需要先卸载旧版，因为旧包曾使用 `versionCode: 1000000`。

当前 HAP 最低要求 HarmonyOS `6.0.2(22)`，分发清单中的 API 版本必须与 HAP 内 `module.json` 保持一致。
