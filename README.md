# installJDK

ここではWindowsOSでのJDKのインストールの方法を示します。

## 1.ダウンロード
以下のリンクをクリック  
[AdoptOpenJDK](https://adoptopenjdk.net/)
>![AdoptOpenJDK](https://github.com/shikari-s/installJDK/blob/master/AdoptOpenJDK.png)
>**Choose a Version**は**12**、**Choose a JVM**は**HotSpot**を選択  

* VersionとJVMを選択したら**Latsest release**をクリック  
**Lateset release**をクリックするとJDKのインストーラがダウンロードされます。  
## 2.インストール  
* ダウンロードが完了したらダウンロードされたソフト(OpenJDK12U-jdk_x64_windows_hotspot_12_33.msi)を起動してインストールを開始します。  
![installer1](https://github.com/shikari-s/installJDK/blob/master/jdk%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%A9%E3%83%BC1.png)  
* 次へをクリック  
![installer2](https://github.com/shikari-s/installJDK/blob/master/jdk%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%A9%E3%83%BC2.png)  
* 内容をよく読みチェックボックスをクリックして次へをクリック
![installer3](https://github.com/shikari-s/installJDK/blob/master/jdk%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%A9%E3%83%BC3.png)  
* 場所:に記しているのはJDKがインストールされている場所なので覚えておくと良い。
* 次へをクリック
## 3.確認
* **インストール**の手順で確認したファイルを開いて以下のファイルがあるかを確認する
  * **bin**
  * **conf**
  * **demo**
  * **include**
  * **jmods**
  * **legal**
  * **lib**
  * **release**  
全てのファイルが確認できればインストール完了となります。
もう一度インストールし直したい場合は、インストーラを起動することで可能です。
