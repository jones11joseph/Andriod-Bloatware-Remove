<title>Andriod Bloatware Remover 2024 </title>
<title>Andriod Debloater 2024 </title>
<title>Andriod Debloater - Google </title>
<title>Andriod Debloater - OPPO </title>
<title>Andriod Debloater - Coloros </title>
<title>Andriod Debloater - Oxygenos </title>
<title>Andriod Debloater - Oneplus </title>
<title>Andriod Debloater - Motorola </title>
<title>Andriod Debloater - List 2024 </title>

# Andriod-Bloatware-Remove 2024 August 30 By Jones Joseph
Andriod-Bloatware-Remove only for users aware adb shell commands 
*******************************************************
Latest Standalone Android SDK Platform Tools package (https://developer.android.com/studio/releases/platform-tools), and enable USB Debugging from Developer options
********************************************************
To Uninstall Apps on Andriod  30 Aug 2024
***************************************
adb shell 
pm uninstall -k --user 0 com.package.name (to uninstall app but keep app data)

pm uninstall --user 0 com.package.name (to delete app and its data both)

********** 
Uninstallation Failed Errors 
*****************

Failure [not installed for 0]: It means the app package you are trying to remove is not installed on your phone.

Failure [delete_failed_internal_error]: You’ll get this error on your device if the OEM has disabled the uninstallation of a system app so you can’t uninstall it.

************* 
Restore Uninstalled System Apps
************* 
In case you uninstall an Oppo system app by mistake, don’t worry. You can re-install it using the following command.

adb shell 
cmd package install-existing com.package.name

************* 
Disable Apps
************* 

adb shell 
pm disable-user --user 0 com.package.name

****************************************
**************** 
To remove Google TV and Google One --- Output from device 
*********
adb shell
* daemon not running; starting now at tcp:5037
* daemon started successfully

guamp:/ $ pm uninstall -k --user 0 com.google.android.videos

Success

guamp:/ $ pm uninstall -k --user 0 com.google.android.apps.subscriptions.red

Success

guamp:/ $
********************************************************

1. For Google App  Name and their package name refer https://github.com/jones11joseph/Andriod-Bloatware-Remove/blob/main/google%20packages%20list

2. For Meta / Facebook App Name and their Package name refer https://github.com/jones11joseph/Andriod-Bloatware-Remove/blob/main/Meta%20Package%20List

3. For Xiaomi / MiUi Debloater tool use https://github.com/jones11joseph/Andriod-Bloatware-Remove/blob/main/Xiaomi%20ADB%20%26%20Fastboot%20Tools.jar

4. For Coloros / OPPO Debloater List use  https://github.com/jones11joseph/Andriod-Bloatware-Remove/blob/main/coloros-debloat
   
6. For Oneplus / Oxygenos Debloater List use https://github.com/jones11joseph/Andriod-Bloatware-Remove/blob/main/oneplus%20oxygenos%20debloat%20list

7. For Motorola / Stock / My UX / Moto UX Debloater List use https://github.com/jones11joseph/Andriod-Bloatware-Remove/blob/main/Moto%20Debloat%20list

   *************************************
Debloater Motorola
WARNING  Below script will completely remove 95% of apps on Motorola phone
use very carefully think twice before use ** End User Responsibility **

