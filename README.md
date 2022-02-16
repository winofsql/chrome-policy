# chrome-policy

[管理対象パソコンに Chrome ブラウザのポリシーを設定する](https://support.google.com/chrome/a/answer/187202?hl=ja)\
[【Google Chrome】ポリシーテンプレートで共有PCの勝手な設定変更を禁止する](https://atmarkit.itmedia.co.jp/ait/articles/1906/12/news018.html)


### 自動入力
![image](https://user-images.githubusercontent.com/1501327/154174337-bb846f65-5aef-4cad-97c4-50e6f5d87ea8.png)

![image](https://user-images.githubusercontent.com/1501327/154174083-fbaf51e4-32b5-4379-b40f-53659b9ac433.png)

[AutofillAddressEnabled](https://chromeenterprise.google/policies/?policy=AutofillAddressEnabled)
```
Software\Policies\Google\Chrome\AutofillAddressEnabled
```

![image](https://user-images.githubusercontent.com/1501327/154174399-7cbb3dd6-b974-46eb-a55d-27af1eb86496.png)

[AutofillCreditCardEnabled](https://chromeenterprise.google/policies/?policy=AutofillCreditCardEnabled)
```
Software\Policies\Google\Chrome\AutofillCreditCardEnabled
```

### ❌ [デバイスから Chrome のデータを自動的に削除する](https://support.google.com/chrome/a/answer/10686330?hl=ja)

[ClearBrowsingDataOnExitList](https://chromeenterprise.google/policies/?policy=ClearBrowsingDataOnExitList)
```
Software\Policies\Google\Chrome\ClearBrowsingDataOnExitList
```

![image](https://user-images.githubusercontent.com/1501327/154178065-433e2abf-332c-413b-9578-3454a54308dd.png)

### ❌ [Google とのデータの同期を無効にする](https://admx.help/?Category=Chrome&Policy=Google.Policies.Chrome::SyncDisabled&Language=ja-jp)

[SyncDisabled](https://chromeenterprise.google/policies/?policy=SyncDisabled)
```
Software\Policies\Google\Chrome\SyncDisabled
```

![image](https://user-images.githubusercontent.com/1501327/154179523-1645df55-cbad-4a30-9474-9df23194f57a.png)

### [パスワード マネージャーへのパスワード保存を有効にする](https://admx.help/?Category=Chrome&Policy=Google.Policies.Chrome::PasswordManagerEnabled&Language=ja-jp)

![image](https://user-images.githubusercontent.com/1501327/154181026-fb5d3da5-8df7-4c0b-94cc-29ec29dc4365.png)

[PasswordManagerEnabled](https://chromeenterprise.google/policies/?policy=PasswordManagerEnabled)
```
Software\Policies\Google\Chrome\PasswordManagerEnabled
```

<br>

![image](https://user-images.githubusercontent.com/1501327/154184046-f2cd70c7-8563-4789-817d-de4d72d4578e.png)


### 起動時

❌ [RestoreOnStartup](https://chromeenterprise.google/policies/#RestoreOnStartup)
```
Software\Policies\Google\Chrome\RestoreOnStartup
```

❌ [RestoreOnStartupURLs](https://chromeenterprise.google/policies/#RestoreOnStartupURLs)
```
Software\Policies\Google\Chrome\RestoreOnStartupURLs\1 = https://example.com
Software\Policies\Google\Chrome\RestoreOnStartupURLs\2 = https://www.chromium.org
```

### デザイン

[ShowHomeButton](https://chromeenterprise.google/policies/#ShowHomeButton)
```
Software\Policies\Google\Chrome\ShowHomeButton
```

❌ [HomepageLocation](https://chromeenterprise.google/policies/#HomepageLocation)
```
Software\Policies\Google\Chrome\HomepageLocation
```

<br>
