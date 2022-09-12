<p align="right">Source: https://www.psx-place.com/resources/henkaku-settings-mod.613/</p>

Everyone, it is long time no see. I think that there are few people who think that "I was doing" for the first time in three weeks. However, I have not played that whole period! I was developing variously with VitaSDK.<br>
I would like to introduce one of them this time. That is "HENkaku Settings Mod".

We also add source to the zip file. If you use only plugins please use only henkaku_ sfc .suprx. The previous plugin should be commented out with # and invalidated before adding another.<br>
**An example**
```
*NPXS10015
#ur0:tai/henkaku.suprx
ur0:tai/henkaku_sfc.suprx
```
When enabling HENkaku, it was possible to change the setting related to HENkaku by setting [HENkaku setting] to the setting, but this time I added a function to that setting. Please add this plugin to * NPXS 10015 in config.txt. If the effect is reflected, items will increase like the image below.

![11.jpg](https://www.psx-place.com/attachments/11-jpg.10575/)

The added function is three items from [Save Console ID (ux 0: CID.bin)].<br>
It is explanation of each function

Save Console ID (ux 0: CID.bin) saves the Console ID of that terminal in ux 0: CID.bin.

Although there is no use at the present moment, it has been set as a possibility to use in the future.

**Mount Settings**<br>
We improved some of the functions of VitaRW and added it.
![22.jpg](https://www.psx-place.com/attachments/22-jpg.10574/)
The main use cases are<br>
I let sleep for a long time and uma 0 ceased to recognize!

What should I do!<br>
When saying Mount Settings> RW Mount> uma 0 Mount<br>
Re-mount uma 0 from will be revived splendidly
![33.jpg](https://www.psx-place.com/attachments/33-jpg.10573/)
![44.jpg](https://www.psx-place.com/attachments/44-jpg.10572/)
![55.jpg](https://www.psx-place.com/attachments/55-jpg.10571/)
![66.jpg](https://www.psx-place.com/attachments/66-jpg.10570/)


Otherwise you can safely remove it from the device by Umount uma0.
![77.jpg](https://www.psx-place.com/attachments/77-jpg.10569/)

Basically, you should not touch this setting (Mount Settings) to other than developers.<br>
Regular HENkaku users should prefer only gro0, grw0, uma0.<br>
If you touch vs 0 badly it will cellbrick.<br>
※ sa0, ur0 which can not be mounted from user land is removed from the item.

Power Settings can restart or shut down the device .<br>
![88.jpg](https://www.psx-place.com/attachments/88-jpg.10568/)
If there are any troubles, bugs, etc., it will be appreciated if you can comment etc.
