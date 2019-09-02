# Tips

<details>
<summary>新規デバイスのUUIDを追加したのにProvisioning profileに反映されない...</summary>

キャッシュが悪さをしている可能性あり。下記手順を試す。

1. XcodeのAuto Signing機能にチェック入れる。
2. `$HOME/Library/MobileDevice/Provisioning Profiles` 直下にあるProvisioning profileを全て消す。
3. 新しいProvisioning profileが生成される。
4. 新規デバイスのUUIDが追加されたPrivisioning profileが作成される。

</details>