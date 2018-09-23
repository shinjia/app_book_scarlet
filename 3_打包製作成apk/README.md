# 請自行完成打包作業


## 測試階段用

- 須修改 config.xml 內的資料
- 使用 PhoneGap Build 上傳
- 線上製作 _____-debug.apk 檔案下載


## 正式上架用

- PhoneGap 的 config.xml 裡需增加SDK的版本設定 (需參考官方最新規定)

```
    <!-- 加入其它plugin設定 -->
    <platform name="android">
        <preference name="android-targetSdkVersion" value="26" />
    </platform>
```
- 須上傳簽署憑証檔案 (xxxxx.keystore)

- 完成 _____-release.apk 檔案下載


## 之後版本更新

- PhoneGap config.xml 裡的版本代碼 versionCode="1" 要更改




