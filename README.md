<p align="center">
  
<img width="200px" src="https://w.nr1.nu/archive/banners/nr1_logo.png" />
  <h2 align="center"># Hack Samsung Galaxy S10 Plus Android 12 - FRPBypass</h2>
  <h3 align="center">(Latest Security Patch from: <i>2022-02-01)</i></h3>
  <h4 align="center">---=== All Models Works And Are Vulnerable IF Android 12 Is Installed ===---</i></h4>
</p>

> :warning: **Patched from 2022-04-01**: you must find your way around, go go hack or die! I dont have any android device anymore so I cant try, if I will get one - I'll update this post! 

<h5 align="center">wuseman cracks the latest security patch AGAIN <br>Where's the challenge Samsung?</h3>

* [More info about the the CVC from Samsung here](https://security.samsungmobile.com/serviceWeb.smsb)

### Security patch version for my device 

#### No worries, I got you covered with a newer version (they  are fast but not fast enough so I decided to share this wiki to the public - This hack works perfect for all Samsung devices with latest securit patch (2022-02-01) while the wiki is created it works awesome still (2022-02-21),.This method  does **NOT** work on Android 11 so you have an Android 11 FPR locked device so you can upgrade to the latest firmware from Samsung)


---

* I never report vulnerabilities to companies, they make their money if you are one of my followers here at [@Github](https://github.com/wuseman) and want to report anything to the idiots feel  feel free, I will succeed again and again and again so for me personally it does not matter BUT it may cause other users so think twice before contacting the companies, they have enough developers to figure out things on their own and be happy as long as it works! My [old screenshot method wich I found ](https://github.com/wuseman/Samsung_Galaxy.s10_FRP.Bypass) some idiot reported this vulnerability was patched fast unfortunately, but for whose benefit? Not to ours, just for the greedy companies out there.


## Now let's hack!

### 1) Start device

### 2) Press start at welcome screen


### 3) Enter "End user license agreement"
 

### 4) Choose wifi network


### Connect to the wifi

### 5) Press volume up + power button


### 6) Draw your finger to right and then up


### 7) Allow talkback record audio: Choose only this time

### 8) Remove always show this message in the popup window

### 9) Now press press use voice commands


### 10) Allow talkback record audio: Choose only this time

### 11) Say **slowly:** 'Google Assistant'

### 12) Bixby will start


### 13) Login to your samsung account


### 14) Accept agreements


### 15) Press cancel when bixy asking for a faster way to sign in


### 16) Press start


### 17) Say "Open Google Chrome"


### 18) Press accept and continue


### 19) Press no thanks on turn on sync


### 20) Browse to ![Nr1](https://android.nr1.nu)


### 21) Scroll down to "Alliance Shield X(Galaxy Store)"

### 22) Install application

### 23) Once done, Alliance Shield X Application, open application


### 24) Press Next in welcome window


### 25) Press next again in permission window


### 26) Press next in privacy promise window


### 27) Press got it on getting started

### 28) Login on your account


### 29) Enter DEVICE Name, in this case: SM-G975F


### 30) Enable Devicew Admin in device setup screen


### 31) Press activate in activate device admin app


### 32) Press next


### 33) Enable knox in samsung knox window, press next


### 34) Press continue in "Knox License Activation"


### 35) You should see "Know license validation completed"


### 36) Press next

### 37) Press finish in import window


### 38) Press app manager in upper left corner

### 40) Press service mode


### 41) Press activities


### 42) Press service mode


### 43) Press open in the popup window


### 44) Choose MTP+ADB and press OK


### 45) Accept adb request


# Now enter ADB from your PC, enter: 

```sh
content insert --uri content://settings/secure --bind name:s:user_setup_complete --bind value:s:1
```

### For all who is interested more deeply, logcat gives us: 

```ini
02-20 23:25:40.306   936  8470 D RestrictionPolicy: isSettingsChangesAllowedAsUser, userId 0 : true
02-20 23:25:40.306   936  8470 D SettingsProvider: ret = 1
02-20 23:25:40.318   936  8470 I GenerationRegistry: mBackingStore.isClosed() : false
02-20 23:25:40.320  5655  5655 I AODSettingsHelper: content://settings/secure/user_setup_complete changed
02-20 23:25:40.322  5655  5655 I AODSettingsHelper: mKey=user_setup_complete, mIntValue=1, mStringValue=null
02-20 23:25:40.322  5655  5655 I AODSettingsHelper: onChange() COMPLETED elapsed= 2
02-20 23:25:40.322  5655  5655 I AODSettingsHelper: **### onSettingsValueChanged for content://settings/secure/user_setup_complete
02-20 23:25:40.322  5655  5655 I AODSettingsHelper: **### onSettingsValueChanged callbackList == null
02-20 23:25:40.323   936  1133 D PackageManager: SetupWizardFinished: true
02-20 23:25:40.323 17664 17664 D hw-ProcessState: Binder ioctl to enable oneway spam detection failed: Invalid argument
02-20 23:25:40.325 17664 17664 D AndroidRuntime: Shutting down VM
02-20 23:25:40.344  5655  5655 I AODSettingsHelper: content://settings/secure/user_setup_complete changed
02-20 23:25:40.346  5655  5655 I AODSettingsHelper: mKey=user_setup_complete, mIntValue=1, mStringValue=null
02-20 23:25:40.346  5655  5655 I AODSettingsHelper: onChange() COMPLETED elapsed= 1
02-20 23:25:40.346  5655  5655 I AODSettingsHelper: **### onSettingsValueChanged for content://settings/secure/user_setup_complete
02-20 23:25:40.346  5655  5655 I AODSettingsHelper: **### onSettingsValueChanged callbackList == null
02-20 23:25:40.346  5655  5655 D DeviceProvisionedControllerImpl: Setting change: content://settings/secure/user_set
```

## Back to mobile device

### 46) Press volume up + power


### 47) Draw right then up


### 48) Say slowly: 'Open Settings'


### 49) When bixby launches, press volume up and power again to turn off talkback settings


### 50) Press record button


### 51) Now say: "Open Account Settings"


### 52) Press add account



### 53) Add your google account


### You are now signing in without any issues


### 54) And you're in!



### As you might notice, you are now signed in.

# ITS NOT DONE!!! 

### DONT JUST RUSH INTO A FACTORY RESE OR SOMETHING, CONTINUE READING..

### 55) Lets head back to welcome screen, turn back as many times as it neededed to get there


### 56) You can now press next, accept license and policies and wifi should already be fixed so press next and you will now see:


### 57) Followed by


### 58) AND HERE IT STOPS! You wont be able to continue, DON'T PANIC!



### 59) Once again, lets get bixy started :) 

### 60) Press volume up + power

### 61) Draw your finger on bottom right then up


### 62) Say 'Google Assistant' and when bixby launches, press volume up and power to turn off talkback settings

### 63) When you hear the beep, slowly say: 'Open Settings'


### 64) Go to "Apps" sections wich has been locked all the time until we added our google account as you probably tried already, settings application crashing when pressing on it but now its unlocked:


### 65) Find "One UI Home" application, press on it

### 66) Press: Set Home Screen


### 67) Select: One UI Home and when you press on it System UI will launch and you bypassing the earlier setup wizard


### 68) And it results in below scren when you press on one ui': 



##### You have just hacked samsung's latest security patch and there are a thousand reasons why i do not use cell phones ;)

## Welcome Screen

### Since adb shell is still open, clear all samsung applications so we can take control over lock settings without any bruteforcing: 

![](https://www.nr1.nu/hacking/android/Samsung_Galaxy.s10_plus_Android.v12.PREVIEWS/clear_all_samsung_apps.gif)
          
```sh
cmd package list packages|cut -d: -f2|egrep samsung > /storage/self/primary/clear.txt 
sed 's/^/pm clear --user 0 /g' /storage/self/primary/clear.txt  > /storage/self/primary/clear_script.sh 
sh -x /storage/self/primary/clear_script.sh 
```

```sh
cmd package list packages|cut -d: -f2|egrep google > /storage/self/primary/clear_google_apps.txt 
sed 's/^/pm clear --user 0 /g' /storage/self/primary/clear.txt  > /storage/self/primary/clear_google_apps.sh
sh -x /storage/self/primary/clear_script.sh 
```

### Your lock settings is NOT disabled if you are using an FRP locked Device, however you can confirm this with cmd:

```sh
cmd lock_settings get-disabled
```

cmd lock_settings is the new way we used locksettings in past (you probably seen my wbruter script wich is very old and slow nowdays, use cmd instead) and since lock_settings was introduced in cmd we simply can use below to disable lock screen without any hacking:

```sh
cmd lock_settings set-disabled true 
```


### Since we still love ADB and working in cli rather then GUI (at least that's me) set your pin code with: 

```sh
cmd locksettings --set-pin XXXX XXX
```

### And for GUI fantasts, open settings and browse to Biometrics and Security either with below command or via your homescreen

```sh
am start -a android.settings.SETTINGS
```

### Add your fingerprint and face recogntion and set your pin
         

### You have just hacked the latest Security Patch from Samsung (2022-02-01)


Send me an email or contact me on ÍRC: 

- **iRC**: wuseman@**Libera**

Enter Libera's network via your own client 'chat.libera.chat:+6697 or use their new web client [here](https://web.libera.chat/).

- **Mail**: wuseman@**nr1.nu**




This tutorial is licensed under the GNU General Public License v3.0 - See the [LICENSE.md](LICENSE.md) file for details - Feel free to copy this wiki but if you do, please share an url to this original post. Thanks alot!

* Happy Hacking and Never Give up!
