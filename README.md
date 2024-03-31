# ros2-for-unity-android-package

**2024/3/31アーカイブ済み**
今後は[ros2-for-unity](https://github.com/Kotakku/ros2-for-unity)のReleasesからunitypackageをダウンロードしてください

ros2-for-unity unitypackage for Android

[ros2-for-unity](https://github.com/RobotecAI/ros2-for-unity)がAndroid端末でも動作するように変更を加えたunitypackage

## 動作確認環境
- Ubuntu22.04 (ROS2 humble)
- Android 9 Pie

## 使い方
- unitypackageをUnityのプロジェクトにimportする
- 本家ros2-for-unityと同じようにスクリプトを書く
- PlatformをAndroidに変更する
- Player Settingsで次の項目を変更する
    - Scripting Backendを「Mono」から「IL2CPP」へ変更
    - Target ArchitecturesのARM64のチェックを入れる
    - Internet Accessを「Auto」から「Require」に変更
- ビルドして実機で動かす

## ビルド
ビルドを自前で行いたい場合は以下を参照のこと  
https://github.com/Kotakku/ros2-for-unity
