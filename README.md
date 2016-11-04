# AndroidやAndroid Sutdioに関するメモ
## Android

## Android Studio
### プラグイン
#### プラグインウィンドウ
File -> Settings -> Plugins

#### おすすめプラグイン
- Kotlin
- Markdown

### ショートカットキー

## 継続的インテグレーション
### 概要
1. Build
1. Unit Test
1. UI Test
1. Inspection
1. Deploy
1. VCS
1. CI

### Build
#### コマンドライン
Debugビルド
```
./gradlew assembleDebug
```

Releaseビルド
```
./gradlew assembleRelease
```

/app/buildにapkファイルが生成される

### VCS
1. VCS -> Enable Version Control Integration -> Git
