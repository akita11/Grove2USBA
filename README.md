# Grove2USBA

<img src="https://github.com/akita11/Grove2USBA/blob/main/Grove2USBA.jpg" width="320px">

Grove端子から電源(+5V)をUSB-Aコネクタ（ソケット）への給電をGrove端子の信号線で制御することができます。

## 使い方

Grove端子をM5Stack等に接続し、給電したい機器をUSB-Aコネクタに接続します。Grove端子の信号線（初期状態では"A"(2番)）を"L"にすると給電され、"H"（または開放）にすると給電されません。

給電したい機器への電力はGrove端子から受けますので、供給側の電力供給が不足する場合は、[「M5Stack USB TypeC2Grove外部電源供給ユニット」(https://www.switch-science.com/products/8453)等をつかって電源を強化してください。


## 設定の変更

<img src="https://github.com/akita11/Grove2USBA/blob/main/Grove2USBA_config.jpg" width="320px">

コネクタへの給電制御をGrove端子の2本の信号線のどちらで行うかを切り替えることができます。

- A(2番): JP2を中央-△マークのある側をショート（初期状態）
- B(1番): JP2を中央-△マークのない側をショート（※中央-△マークのある側のパターンをカットしてください）


## 使い方（オプション）

給電のためのUSB-Aプラグ、またはUSB-Cコネクタを追加でとりつけ、そちらから給電することができます。

- USB-Aプラグ: [秋月電子・USB-4AM103AS](https://akizukidenshi.com/catalog/g/g102236/)等
- USB-Cコネクタ: [秋月電子・UJC-HP-3-SMT-TR](https://akizukidenshi.com/catalog/g/g116438/)等＋5.1kΩチップ抵抗(0603/1608)x2個

<img src="https://github.com/akita11/Grove2USBA/blob/main/Grove2USBA-op1.jpg" width="320px">

<img src="https://github.com/akita11/Grove2USBA/blob/main/Grove2USBA-op2.jpg" width="320px">

## Author

Junichi Akita (akita@ifdl.jp, @akita11)
