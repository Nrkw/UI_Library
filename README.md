# UI_Library
Bluetoothライブラリを使用してゲームを作成するときに便利なUIライブラリ
#概要
Bluetoothライブラリを利用してゲームを作る時に必要となるUIを用意したライブラリ。
[Bluetoothライブラリ](https://github.com/Nrkw/Bluetooth_Library)を使用していること前提です。

#導入方法
1. まず、この[Bluetoothライブラリ](https://github.com/Nrkw/Bluetooth_Library)をダウンロードし、使用できるようにします。
2. このライブラリをクローンし、uiディレクトリの中に格納します。
3. compile.batを作成
```
MinGW13.1.0¥bin¥g++ main.cpp -lbluetooth -lui
```
```
working_folder(自分で作成)/
├── MinGW13.1.0
├── bluetooth(Bluetoothライブラリ)
├── ui(このライブラリ)
├── compile.bat
└── main.cpp(ここにメインのプログラムを書いていく)
```
このようなファイル構成になっていることを確認してください。