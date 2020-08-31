# ディスプレイデバイス情報 Readme
コンピューターに接続された全てのアクティブモニターの各種情報を表示します。

[ゆっくりするブログ : ディスプレイの物理的なサイズを取得する](http://jag5.dreamlog.jp/archives/7949249.html)に記載のコードをベースにしています。

# 動作要件
Microsoft Windows XP Service Pack 3以降(IA-32/AMD64/AArch32/AArch64)

# 実行手順
**bin** の中にある以下の実行ファイルの中から、ご使用のコンピューターに合ったものを実行してください。メッセージボックスの形で結果が表示されます。
- DDI_IA-32.exe : 32ビット(x86)
- DDI_AMD64.exe : 64ビット(x86)
- DDI_AArch32.exe : 32ビット(ARM)
- DDI_AArch64.exe : 64ビット(ARM)

# インストール・アンインストールについて
このソフトウェアはインストール不要です。削除も、そのまま実行ファイルを削除するだけで大丈夫です。レジストリなどは使用していません。

# ソースコードについて
ソースコードは、**src** にあります。ビルド方法などは **src** 内のreadmeを参照してください。

# 使用上の注意
製作者は、このプログラムの利用によって生じた、いかなる損害についても責任を負いません。

# 著作権情報など
このソフトウェアは[ゆっくりするブログ : ディスプレイの物理的なサイズを取得する](http://jag5.dreamlog.jp/archives/7949249.html)に記載されているコードに独自の機能を追加する形で制作しました。

私が追加した部分に関しては著作権を放棄しますが、**出典サイトの方は著作権を放棄していない可能性があるため、転載などを行う際は確認をとることをお勧めします**。

# 変更履歴
## v1.01 (2020/8/30)
ソースコードを見直し、若干の効率化を図った。

## v1 (2019/4/5)
初回リリース