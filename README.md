# WinProVirtualKey
## Cracked Windows Activation Program

### Want to explore Windows in Pro version or just experiment with it? Try Windows EE Pro for free with this script!
### Download it for free!
Activation should take 3-5 minutes!
<b>WORKS ONLY ON WINDOWS 10 AND WINDOWS 11</b>


# Instructions:

1. Run `WinProVirtualKey(VER).exe`

> <span style="color: red;">Note: If when running `WinProVirtualKey(VER).exe`, the `User Control` window is not displayed, terminate the process and run `WinProVirtualKey(VER).exe` with <b>`Right Click` -> `Run as administrator`</b></span>

2. Wait for `WinProVirtualKey(VER).exe` to finish the whole script (see fifth screenshot)

3. After finishing the script, run `OptionalFeatures.exe` and check the `Windows Identity Fundation 3.5` option for the correct operation of the system if an error occurred during the execution of the script that no such license (or version) was found

> <span style="color: red;">Note: Don't worry, your system will be activated, but it's still worth checking this option!</span>

4. Restart your computer <i>OR</i> `Control+Shift+Enter` -> `shutdown -r`

5. Check that everything is working properly

> <span style="color: red;">Note: If the system still hasn't been activated, download and run `kms-repair.exe` or follow the instructions below "If <b>Key Management Service</b> is not working properly"</span>

6. You've activated your Windows!

# Notes:

1. Run WinProVirtualKey(VER).exe with administrator priviliges!

2. KMS (Key Management Service) may malfunction, it can be fixed, and to solve this problem:
    - Restart the system
    - Renew *KMS* and its services
    - Disconnect from your organization's network (if your device is on one)
    - Make sure that no Windows license has been activated while executing the script
    - Check in the console that _DISM_ (_Deployment Image and Management Tool_) has been started correctly and is executing commands (check the picture below) that are important when performing functions from _KMS_

3. Disable your antivirus for the script to work properly (this script is considered harmful by antiviruses, but it really isn't) or head to "How to enable WinProVirtualKey" as safe?"

**4. USE THIS SCRIPT AS A WINDOWS ACTIVATION TOOL ONLY AND SOLELY AT YOUR OWN RISK AND ONLY ON A VIRTUAL MACHINE**

### If <b>Key Management Service</b> is not working properly:

<i>(You can also download kms-repair.exe from this repository to do this faster - of course with administrator priviliges!)</i>

1. Hit `Control+Shift+Enter` to enter to the CMD
2. Type these commands: `slmgr.vbs /upk` -> `slmgr.vbs /cpky` -> `slmgr.vbs /ckms` -> `slmgr /skms kms8.msguides.com` -> `slmgr /ato` -> <i>Reboot</i>
3. Run `WinProVirtualKey(VER).exe` (<b>WITH ADMINISTRATOR PRIVILIGES!</b>)


## How to enable `WinProVirtualKey` as safe?

I'll show you how to do it using *Windows Defender* as an example:

1. Run `Windows Security`

![image](https://user-images.githubusercontent.com/83708878/222959918-aeae8a49-ae4d-482b-aa91-df33518eadda.png)

2. Go to `Virus and threat protection` section

![image](https://user-images.githubusercontent.com/83708878/222959968-887d93c9-6eb6-4c60-bba9-0af700ace230.png)

3. Click on the latest threat (usually named `Trojan:Win32/Wacatac.H!ml`)

![image](https://user-images.githubusercontent.com/83708878/222960005-0c0b7bc9-5c7b-42e3-a2cf-3b52996b3b3b.png)

4. Select `Allow on device` and then click `Start actions`

![image](https://user-images.githubusercontent.com/83708878/222960057-c8aa92cb-1881-4bd5-b7c5-d7e1341519df.png)

> Note: Most often, after allowing, you need to disable `Virus Protection` and re-enable it after `WinProVirtualKey` completes the script

5. Redownload (if it has been removed) and click `Keep` (or `Keep anyway` in the next window)

![image](https://user-images.githubusercontent.com/83708878/222960108-634658a0-a070-4f3b-814a-ef9934a69fdd.png)

<br></br>

# Screenshots:
![image](https://user-images.githubusercontent.com/83708878/222952393-258a3b62-5c96-4950-baf2-a2d0a46c6433.png)

<i>Running the script.</i>

![image](https://user-images.githubusercontent.com/83708878/222952436-9ad9d1bb-0d27-452f-8ddf-7c0882c8ab52.png)

<b>NOTE: "Professional" is needed in this section, if the license list shows all versions without "Professional", try to renew KMS</b>

![image](https://user-images.githubusercontent.com/83708878/222952525-5c9b6573-0082-4163-98fb-ec575988b0ca.png)

<i>Make sure you have received this message, otherwise try again.</i>

![image](https://user-images.githubusercontent.com/83708878/222952595-e143cdbb-0b2b-47a2-8e75-502fa6159bc8.png)

<i>Make sure KMS is redirected to `kms8.msguides.com`.</i>

![image](https://user-images.githubusercontent.com/83708878/222952767-f4e303ee-cb69-4318-bf76-25a60e12d079.png)

**You've finally activated your Windows Pro!**





### <b>W A R N I N G :   THIS PROGRAM IS FOR FULL VIRTUAL MACHINE WINDOWS LICENSE ONLY - YOU ARE RESPONSIBLE FOR VIOLATIONS OF MICROSOFT AND AFFILIATES' PRIVACY POLICY AND TERMS OF CONDUCT - DO NOT CONTINUE IF YOU ARE NOT SURE OF THE LEGALITY OF YOUR ACTIVITIES! I'M NOT RESPONSIBLE FOR YOUR ACTIONS!</b>
