# Mine-imator 日本語化ガイド
![img1](https://github.com/harujun214/mineimator-jp/raw/main/img/img1.png)
## 目次
* [前提](#前提)
* [導入方法](#導入方法)
## 前提
新しいプロジェクトを作る際にタイトルや作者名を日本語で入力すると、**文字化け**してしまう現象があります。その原因は、Mine-imatorで使われているフォントが**日本語に対応していない**ためです。
つまり、日本語化にしただけでは文字化けしてしまいますので、日本語化にするための**日本語フォント**が**必須**になります。  

日本語フォントについては好みでいいと思います。「フリーフォント おすすめ」「見やすい フリーフォント」で検索をかけると、色々なフォントが出てきます。ただし、使うフォントによっては含まれていない文字があったりしますので、最低でも**漢字**と**半角カナ**まで使えるフォントを選ぶようにしてください。一部の文字が表示しきれずに見切れてしまう対策として、半角カナも含まれてます。

Mine-imatorでは基本**TrueTypeのみ対応**ですが、 **.otf** のフォントでも拡張子を **.ttf** に変更しても使えるので、フォントを決める際にあまり気にする必要はありません。  
<details>
<summary>例：Noto Sans JP</summary>
  
  「 [Noto Sans JP - Google Fonts](https://fonts.google.com/noto/specimen/Noto+Sans+JP) 」にアクセスし、右上にある **Download Family** をクリックします。
  ![nsjp1](https://github.com/harujun214/mineimator-jp/raw/main/img/nsjp1.png)
  ダウンロードできたら、圧縮ファイルをダブルクリックして中に入ってる「 **NotoSansJP-Medium** 」を取り出します。
  ![nsjp2](https://github.com/harujun214/mineimator-jp/raw/main/img/nsjp2.png)
  フォント形式が **otf** になっているので、 **ttf** に変えます。ファイルが使えなくなる可能性がありますと出ますが、「はい」をクリックします。
  ![nsjp3](https://github.com/harujun214/mineimator-jp/raw/main/img/nsjp3.png)
  
</details>

## 導入方法
Mine-imatorがインストールしてあるフォルダーを開きます。デフォルトは **C:/Users/(ユーザ名)/Mine-imator** になります。

そのフォルダ内の **Data** > **Languages** フォルダーを開き、先程ダウンロードしたファイルを移動させます。上書きの確認が表示された場合は「**ファイルを置き換える**」を選択します。
