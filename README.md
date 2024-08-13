# M5 Atom JoyStick の内蔵ファームウェア を STM32CubeIDE でビルドできるようにしてみた版

- 元のリポジトリ https://github.com/m5stack/Atom-JoyStick-Internal-FW/

## やったこと

1. 元のプロジェクトの .ioc ファイル( Fly_Remoter_2.ioc ) を STM32CubeIDE にインポートし、コード生成する。
2. 元のプロジェクトの Core フォルダ以下のヘッダやソースコードを上書きする
3. ビルドする
4. 動かない場所を探す（今回は、IAP_Set() 関数)

## 関連項目

- STM32CubeIDEでHEXファイルを作成する方法 https://yukblog.net/stm32cubeide-hex/

