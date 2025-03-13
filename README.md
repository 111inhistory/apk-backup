# xuehai-crack

This repo is aiming to gathering informations.

## Some Already Fixed Bugs

- otg: with an otg cable, you can connect USB devices, like keyboards, DictPen.

  Fixed on version 20220323

- Files: Activity name is `com.android.documentsui.files.FilesActivity`, it can be open by connecting the DictPen or other MTP supported devices (like your mobile phone)

  Fixed the opening method of otg by version 20220323
  While version 20220830 would force to close non-xuehai app at login and force to close all the apps background, it's easy to be closed. 

- Keyboard&Mouse: Though the ban of USBHostStorage banned the connection of OTG adapter, it's still possible to use scrcpy running on Linux to simulate a keyboard & mouse, but it seems of no use.

  Some interesting facts:
  1. The mdm didn't discover a usb device.
  2. When on the display of xuehai home,it will be disconnected from computer, and you must reconnect the cable.

- Samsung Dex: It could be opened by keyboard use hotkey`Win+W`, and it's seems no use now (it once useful as it can open other apps like Files above)

## List Some Possible Methods

1. SSL phishing.
2. Dynamic Code Library Decompiled. The lib `lib*******.so` haven't been changed since 20210719. 
Update: changed around 2022 May, but remain the same since then
3. (Not very possible since we reported this Social Engineering Method)Let Xuehai teacher reset the tablet. If the teacher is not trained, you can get the tablet, close the WiFi to avoid the autoupdate of apps when he/she is unconscious. Then, crack it through NDay holes.
4. If multi-activity button is available, go directly into two-depth settings, go back to the upper setting, and press the back button on the left-upper and the multi-activity button. Go back to Settings, you'll found something flashed. Just press the button quickly.
5. Xuehai seems disabled the apk installation, however you can install by enter the view, and switch the light/dark mode of the system.
