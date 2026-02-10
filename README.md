# PicoMZ700
MZ-700 Emulator for MachiKania-P with Raspberry Pi Pico 2

MachiKania-P ボード上で、簡単そうで異常に難しいパズルゲーム、「プチロポコ」を楽しめます。

# 遊び方
- MachiKania-PボードとRaspberry Pi Pico2を入手します(Pico2(RP2350)専用です)。
- [BOOTH]( https://booth.pm/ja/items/5625243 )からプチロポコを買います。(宣伝)
- SDカードを用意して、ルートに'MZROM'フォルダを作成し、プチロポコのZIPファイル内にある'NEWMON7.ROM'と'MZ700FON.JP'をコピーします。
- 'MZROM'フォルダの下に'MZTAPE'フォルダを作成し、'PETITE.MZT'をコピーします。
- MachiKania-Pボードに、GP2(Raspberry Pi Pico2ボードの4pin)に繋いだボタンを追加します。
- [PlatformIO]( https://platformio.org/ )でビルドしてRaspberry Pi Pico2に書き込みます。
- ここまでくれば多分プチロポコ動きます。FIREボタン…決定ボタンorアイテムを使う、STARTボタン…やりなおし、追加したボタン…ゲーム終了です。
- 50面クリアを目指します。

# ごめん
- ひとりで楽しむために作ったので、いくつか致命的な機能がありません(セーブ・ロードとか)。あとオンチです(8253よくわからない)。