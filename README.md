# M5Stack_RunCPM_vt100_UsbKB
M5Stackで動く超小型CP/Mマシン(USBキーボード版）


"VT100 Terminal Emulator"と"Z80 CP/M 2.2 emulator"を組み合わせた、M5Stackで動く超小型CP/Mマシンです。<br>
(注意：ディスプレイが1行53文字のなので、1行80文字を前提にしているプログラムは表示が崩れます。)<br><br>
ベースにしたオリジナルはこちら。<br>
VT100 Terminal Emulator for Arduino STM32 <https://github.com/ht-deko/vt100_stm32><br>
RunCPM - Z80 CP/M 2.2 emulator <https://github.com/MockbaTheBorg/RunCPM><br>

---

### 必要な物 ###
* [M5Stack](http://www.m5stack.com/ "Title") (Fireで動作確認をしました。)<br>
* Arduino IDE (1.8.13で動作確認をしました。)<br>
* [Arduino core for the ESP32](https://github.com/espressif/arduino-esp32 "Title")
* [LovyanGFXライブラリ](https://github.com/lovyan03/LovyanGFX "Title")
* [SDdFatライブラリ](https://github.com/greiman/SdFat "Title") (1.1.4で動作確認をしました。2.x.xではコンパイルエラーになります。)
* [M5Stack用MAX3421E搭載 USBモジュール](https://www.switch-science.com/catalog/6061/ "Title")
* [USB_Host_Shield_Library_2.0](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Module/USB/Arduino/Library "Title") (本家のものとはピン割り当てが異なりますのでこちらのリンク先の物を使用してください。)
* microSD カード
* USBキーボード
<br>


---

### 参考資料 ###
RunCPM用のディスクの作り方などは、DEKO（@ht_deko）さんのこちらの記事を参照してください。<br>

* [RunCPM (Z80 CP/M 2.2 エミュレータ)](https://ht-deko.com/arduino/runcpm.html "Title")<br><br><br>



