# Build guide

back side of PCB（PCBの裏面）


![](img/img00003.jpg)


## Build 1

### 1 Diode soldering

![](img/img00006.jpg)


Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
There are lead type and SMD diodes.
<br>
ダイオードはリードタイプか、SMDがあります。
<br>
Here, we will explain the lead type soldering.
<br>
ここでは、リードタイプのハンダ付けの説明をします。
<br>

![](img/img00004.jpg)





Use a lead bender to bend the legs of the diode.
<br>
リードベンダーを使い、ダイオードの足を曲げます。
<br>
Insert the diode into the board.
<br>
ダイオードを基板に挿しこみます。
<br>

Please pay attention to the orientation of the diode.
<br>
ダイオードの向きに注意してください。
<br>

![](img/img00005.jpg)

Please solder.
<br>
はんだ付けをしてください。
<br>
<br>
Then, cut off the excess lead with nippers.
<br>
その後、余ったリードをニッパーで切り取ってください。


[８倍速　Diodeハンダ付け動画](https://youtu.be/Yaodh2-XxV4)

<br>
<br>


### 2 Switch socket soldering

![](img/img00007.jpg)

Solder the switch sockets on the back side.
<br>
裏面にスイッチソケットのハンダ付けをします。
<br>

![](img/img00008.jpg)


[８倍速　Switch socketハンダ付け動画](https://youtu.be/E__mHvmIXQo)



### 3 Reset switch soldering

Insert the reset switch from the back of the PCB and solder the exposed part.
<br>
リセットスイッチをPCBの裏面から差し込んで、表面に出た部分をはんだ付けしてください。
<br>

![](img/img00009.jpg)

![](img/img00010.jpg)

![](img/img00011.jpg)


### 4 Battery parts soldering(Bluetooth option)

![](img/img00012.jpg)

Solder the slide switch first.
<br>
最初にスライドスッチをはんだ付けします。
<br>
![](img/img00013.jpg)

Insert the switch from the back of the PCB with the switch knob facing outward.
<br>
スイッチのつまみが外側に向くようにして、PCBの裏面から差し込みます。
![](img/img00018.jpg)

After temporarily fixing it with masking tape, etc., solder the exposed part of the PCB.
<br>
マスキングテープなどで仮固定をしてから、PCBの表面に出た部分をはんだ付けします。
![](img/img00019.jpg)
<br>
Next, solder the capacitor.
<br>
次に、コンデンサをはんだ付けします。
<br>
<br>
First, apply solder to only one side of the two pads.
<br>
最初に、２つあるパッドの片側だけに、はんだを盛り付けます。
![](img/img00015.jpg)

Place the capacitor and fix it by melting the solder.
<br>
コンデンサを置き、もったはんだを溶かしながら、固定します。
<br>
Solder the capacitor, applying solder to the remaining pads.
<br>
残りのパッドにはんだを盛りながら、コンデンサをはんだ付けします。
![](img/img00016.jpg)
Finally, attach the battery holder.
<br>
最後に、電池ホルダを取り付けます。
<br>
Insert it from the back side of the PCB and solder the front side. Using masking tape for temporary fixation will make the work easier.
<br>
PCBの裏面から差し込んで、表面をはんだ付けします。仮固定にマスキングテープを使うと作業が簡単になります。
<br>
![](img/img00020.jpg)

![](img/img00021.jpg)




### 4 Install firmware


Install QMK_Firmware from your PC to RP-2040Zero.
<br>
QMK_FirmwareをPCからRP-2040Zeroにインストールしてください。
<br>
<br>
① Download https://github.com/telzo2000/cool336/blob/main/firmware/cool336_vial.uf2 to your PC.
<br>
① https://github.com/telzo2000/cool336/blob/main/firmware/cool336_vial.uf2　
をPCにダウンロードしておく。

<br><br>
② Connect the PC and RP-2040Zero with a USB cable.
<br>
②PCとRP-2040ZeroをUSBケーブルで繋ぐ。
<br><br>
③Press the reset button while pressing the boost button on the RP-2040Zero.
<br>
③RP-2040Zeroのboostボタン押しながら、resetボタンを押す。
<br><br>
④Since there is a folder of RP-2040Zero on the PC screen, drag and drop the downloaded cool336_vial.uf2 there.
<br>
④PC画面にはRP-2040Zeroのフォルダがあるので、そこに、ダウンロードしたcool336_vial.uf2をドラッグアンドドロップする。
<br><br>

⑤Check if it is recognized by connecting to [vial](https://get.vial.today/). Edit the keymap accordingly.
<br>
⑤[vial](https://get.vial.today/)に繋いで認識するかどうか確認する。合わせてキーマップの編集をする。

### 5 Fix the stabilizer

Attach the stabilizer to the surface of the PCB.
<br>
PCBの表面にスタビライザーを装着してください。
<br>

![](img/img00003.jpg)


The stabilizer will operate smoothly if it is greased.
<br>
スタビライザーはグリスをしておくと、滑らかに稼働します。
<br>
<br>

### 6a Fix the switch plate(3D Print) with screws

Place the 3D printed switch plate on the surface of the PCB.
<br>
3Dプリンタで印刷されたスイッチプレートをPCBの表面に載せます。
<br>

![](img/img00004.jpg)

Insert four M2 screws (8mm) from the surface and secure with M2 spacers (3mm) on the back side of the PCB.
<br>
表面からM2ネジ（8mm）を４本挿して、PCB裏側でM2スペーサー（3mm）で固定してください。
<br>

![](img/img00005.jpg)



### 6b Fix the switch plate(Acrylic) with screws

Insert the acrylic switch plate, the M2 spacer (3mm), and the M2 screw (8mm) in that order to secure it.
<br>
アクリルのスイッチプレート、M2スペーサー（3mm）の順でM2ネジ（8mm）の順で差し込んで固定します。
<br><<br>
Place the switch plate on the surface of the PCB.
<br>
スイッチプレートをPCBの表面に載せます。
<br><br>
Fix it with M2 spacer (3mm) on the back side of the PCB.
<br>
PCB裏側でM2スペーサー（3mm）で固定してください。
<br><br>


### 7 Insert the key switch

Insert the key switch from the switch plate side.
<br>
スイッチプレート側からキースイッチを差し込んでいきます。
<br>
<br>
![](img/img00006.jpg)

Due to the characteristics of the switch plate printed with a 3D printer, the square hole of the key switch may be tight. In that case, use a cutter or other bladed tool to scrape off the burr inside the square hole.
<br>
スイッチプレートは3Dプリンタで印刷した特性により、もしかしたら、キースイッチの四角穴がきついことがあります。その時は、カッターなど刃物で四角穴内側のバリを削り取ってください。
<br>

![](img/img00007.jpg)


### 8a Fix the bottom plate with screws

With the PCB facing backwards, secure the bottom plate with four M2 screws (4mm). There is a recess with a diameter of 5 mm and a depth of about 1 mm on the top surface of the bottom plate. Make sure that the M2 spacer fits there.
<br>
PCBを裏側にして、ボトムプレートをM2ネジ（4mm）４本で固定してください。ボトムプレートの上面には1mmほどの深さの直径5mmの凹部があります。そこに、M2スペーサーがはまるようにしてください。
<br>
![](img/img00008.jpg)
![](img/img00009.jpg)

### 8b Fix the bottom case with screws

PCBを裏側にして、ボトムケースをM2ネジ（4mm）４本で固定してください。ボトムプレートの上面には1mmほどの深さの直径5mmの凹部があります。そこに、M2スペーサーがはまるようにしてください。
<br>



<br>
To prevent the RP2040-Zero from falling inside the case when the cable is connected or disconnected, we recommend placing the enclosed sponge under the USB insertion slot.
<br>
ケーブルの抜き差しにより、RP2040-Zeroがケース内部で落下することを防ぐため、同封したスポンジをUSB挿入口の下につけることを推奨します。
<br>
<br>


### 9 Complete

Attach your favorite keycaps and you're done.
<br>
お気に入りのキーキャップをつけて完成です。
<br>
![](img/img00010.jpg)

<br>
Welcome to the world of the best keyboards.
<br>
最高のキーボードの世界にようこそ。
<br>