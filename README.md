# CyberReflector

CyberReflectorは、C++のゲームエンジンSiv3dを用いて作られた一画面全方位シューティングゲームです。<br>
自分から攻撃はできず、敵の弾を反射して戦うのが大きな特徴です。

![ScreenShot](https://user-images.githubusercontent.com/40136659/80856754-9a92b180-8c87-11ea-9c7e-20261dd9de6c.png)


[こちらのリンク](https://github.com/KoheiTashiro/CyberReflector/releases/download/tags/CyberReflector.zip)より、ゲームをダウンロードできます。zipファイルを解凍し、フォルダ内のexeファイルを実行してください。  
本作品は、Windowsでのプレイを想定しています。


開発エンジン:Siv3d(August2016v2)  
使用エディタ:Visual Studio 2015

本作品は大学2年生の時に、サークル活動の一環として個人で製作しました。

### プロジェクトをクローン・ビルドする際の注意
- サイズが大きい Siv3D の Engine フォルダを除外しています。必要な Engine フォルダは他の Siv3D プロジェクトからコピーしてください。
- 必ず使用されるインクルードファイルに、"stdafx.h"を指定してください。
