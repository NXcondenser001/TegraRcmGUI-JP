![Png](https://img.shields.io/badge/platform-windows-lightgrey)
![Png](https://img.shields.io/badge/latest%20stable%20release-2.6-yellow)
![GitHub](https://img.shields.io/github/license/eliboa/TegraRcmGUI)
![GitHub All Releases](https://img.shields.io/github/downloads/eliboa/TegraRcmGUI/total)
![GitHub repo size](https://img.shields.io/github/repo-size/eliboa/TegraRcmGUI)
![GitHub issues](https://img.shields.io/github/issues/eliboa/TegraRcmGUI)

# TegraRcmGUI-JP
rajkostoによるTegraRcmSmashのC++GUI （Nintendo SwitchのFuséeGeléeエクスプロイト）

elinoaによるTegraRcmGUIを日本語化したものです。慣れてしまえば困ることはないと思いますが、日本語にして使いやすくしました。

これは、「未対策機」つまり2018年7月より前に製造されたものでのみ機能します。未対策機かどうかを確認するには、https://ismyswitchpatched.com/ を使用します。

※eliboa様（TegraRcmGUI製作者）の確認を取ってあります。
## 特徴
-ペイロードを送信する

-お気に入りを管理する

-スイッチでLinuxを実行する（ShofEL2）

-デバイスをUSBマスストレージとしてマウントする（SDカードとNANDパーティションの読み取り/書き込み、電源ボタンを5秒間押し続けて終了する）

-eMMCコンテンツ復号化用のBISキーをダンプする（rajkostoによるbiskeydump）

-オプション-「自動注入」：選択後またはスイッチがRCMモードで接続されている場合に、ペイロードを自動的に送信する

-オプション-アプリを最小化してトレイとトレイアイコンのコンテキストメニューに

-オプション-Windowsの起動時にアプリを実行する

-APXデバイスドライバーをインストールする（必要な場合）

-日本語化された使いやすいUI

<img width="272" alt="スクリーンショット 2022-04-13 195842" src="https://user-images.githubusercontent.com/103568351/163166460-71944b81-2ecb-486f-8a24-9f304b39b075.png"><img width="276" alt="スクリーンショット 2022-04-13 195924" src="https://user-images.githubusercontent.com/103568351/163166377-5d813ecb-b58e-4e4f-b910-4b0550475d38.png">

## 注意
これはwindowsでのみ使用できます。 
ほかのプラットフォームではこれらを使用できます :
- [Fusée Launcher](https://github.com/Cease-and-DeSwitch/fusee-launcher) (GNU/Linux)
- [NXBoot](https://mologie.github.io/nxboot/) (OS X, iOS)
- [JTegraNX](https://github.com/dylwedma11748/JTegraNX) (Windows, OS X, GNU/Linux)
- [NXLoader](https://github.com/DavidBuchanan314/NXLoader) (Android)
- [Web Fusée Launcher](https://fusee-gelee.firebaseapp.com/) (Cross-platform, only works with Chrome)


## 発達(?)
セットアッププログラムを使用してlibusbk開発キットをインストールLIBUSBK_DIRし、インストールパスを値として使用して環境変数を作成します。

## Nintendo SwitchのNANDをバックアップ/復元する方法は？

 1) [memloader](https://github.com/rajkosto/memloader) v3 を使用して、コンピューターにeMMCをマウントします
 2) [NxNandManager](https://github.com/eliboa/NxNandManager) をダウンロードして開きます。[ファイル]、[ドライブを開く]の順に選択します。
 3) マウントされたドライブを選択します。これで、バックアップ/復元操作を実行できます。  

<img width="272" alt="スクリーンショット 2022-04-13 195908" src="https://user-images.githubusercontent.com/103568351/163166631-83ef1bd3-fe91-47ab-8450-4f80f2b23718.png">

## クレジット
- [Rajkosto](https://github.com/rajkosto) / [TegraRcmSmash](https://github.com/rajkosto/TegraRcmSmash) , [memloader](https://github.com/rajkosto/memloader), [biskeydump](https://github.com/rajkosto/biskeydump)
- [Kate Temkin](https://github.com/ktemkin) / [Fusée Launcher](https://github.com/Cease-and-DeSwitch/fusee-launcher)
- [fail0verflow](https://github.com/fail0verflow) / [ShofEL2](https://github.com/fail0verflow/shofel2)
- [SciresM](https://github.com/SciresM) / [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
- [CTCaer](https://github.com/CTCaer/hekate)  / [Hekate](https://github.com/CTCaer/hekate)
- [Reisyukaku](https://github.com/Reisyukaku/) / [ReiNX](https://github.com/Reisyukaku/ReiNX)
- [eliboa](https://github.com/eliboa) / [TegraRCMGUI](https://github.com/eliboa/TegraRcmGUI)

## For foreigners
This is a Japanese version of Tegra Rcm GUI by eliboa.

There are no major changes to the contents of REDME.md or zip.

雑な翻訳なのは許してください。

基本はreleaseのとこみてください。そこ以外は基本改変しません。

一部エラーにより翻訳できていません。

お問い合わせはDiscordまでお願いします。"condenser001#6785"

Please enjoy.
