[original]: https://mega.nz/file/FHwglb7a#D294kB3xZaS4t_iiqeUML9XCcNBWdzs5oz6Iefcae3g
[duplicate]: https://mega.nz/file/QagRCKRC#VhJ3FfoTLgFZYNZXHGSBOkdITporIWwJE3x19hlsXIo
[business]: https://mega.nz/file/ka4SxAAJ#qwz8SXoV_3PNJXIy-jK3RiAnU6aN88AVMnOVJE2frfw

[original-nofix]: https://mega.nz/file/YbwRxAJB#gmszMqDzOSJCwsCCAvDMW4AODxbvy_0cn6olawGCYhc
[business-nofix]: https://mega.nz/file/QKJinByZ#qhEzlKWTobQkiiEdpuJ68yzskJ9a3W_e75y8AHV963Q

[builds-io-watusi]: https://builds.io/apps/watusi/?aid=1025553
[builds-io-watusi-duplicate]: https://builds.io/apps/duplicatewhatsappwatusi/?aid=1025553
[builds-io-watusi-business]: https://builds.io/apps/whatsappb/?aid=1025553

<h1 align="center">
Watusi for WhatsApp
</h1>
<p align="center">
The all-in-one tweak for WhatsApp Messenger!
</p>

## Download Links

### Jailbroken Devices

Add __[https://apt.fouadraheb.com](https://apt.fouadraheb.com)__ to your Cydia/Zebra/Sileo sources and download it from there. 

(Check [this page](https://appledb.dev/device-selection/) for more info on how to jailbreak your device if possible)

### Sideloading (No Jailbreak)

1. (Option 1) Download IPA file from here and follow the [instructions below](#sideloading-with-altstore) to sign and install the app from your computer.

    The following IPA files have `Plugins` folder deleted and includes some fixes to avoid WhatsApp crashing when not signed with proper entitlements and a developer account.
    | Application | Bundle | Version | Watusi 3 | Stalky | OnlineNotify |
    | ------------------ |:---------:|:------:|:------:|:------:|:------:|
    | [WhatsApp][original] | net.whatsapp.WhatsApp | 23.15.0 | 1.1.66 | 4.1.22 | 3.4.3 |
    | [WhatsApp Duplicate][duplicate] | com.fouadraheb.watusi | 23.15.0 | 1.1.66 | 4.1.22 | 3.4.3 |
    | [WA Business][business] | net.whatsapp.WhatsAppSMB | 23.14.82 | 1.1.66 | 4.1.22 | 3.4.3 |

    ```Stalky and OnlineNotify tweaks are disabled by default and can be enabled from inside Watusi Settings.```
    
2. (Option 2) [Optional] You can get a paid subscription from a signing store where you can download the latest Watusi directly from your device and have it available for 1 year instead of 7 days. I recommend using [builds.io][builds-io-watusi] since they always have the latest IPA from here. Builds.io links: [Watusi][builds-io-watusi] - [Watusi Duplicate][builds-io-watusi-duplicate] - [Watusi WhatsApp Business][builds-io-watusi-business].

## Sideloading Guides

<details>
<summary><h2>Sideloading with AltStore</h2></summary>

### Requirements

1. A computer running macOS or Windows
2. Internet connection
3. Apple ID (email & password)
4. If you are on iOS 16, you may need to enable Developer Mode. (Settings > Privacy & Security > Developer Mode)

### AltStore

* Download the IPA file from the link above and copy it to your phone, using iCloud Drive, Airdrop, or any other method.

* Download and install AltServer from [here](https://altstore.io)

* Right-click on the AltServer icon with your phone connected and choose "Install AltStore", then the name of your phone. When prompted sign in with your Apple ID. Two-factor Authentication is supported, but app-specific passwords are not.

* Make sure no other WhatsApp with the same bundle identifier is installed. (net.whatsapp.WhatsApp if you chose the original IPA or com.fouadraheb.watusi for the duplicate)

* Open AltStore and navigate to the "My Apps" tab. Choose the plus in the top right corner and open the IPA file. When prompted sign in with your Apple ID. Two-factor Authentication is supported, but app-specific passwords are not.
</details>

<details>
<summary><h2>Sideloading with TrollStore (iOS 14 - 15.5 b4*)</h2></summary>

Available for <b>iOS 14 - 15.1.1</b> (All devices) and <b>iOS 14 - 15.5 b4</b> (iPhone X and older)

1. Install [TrollStore](https://github.com/opa334/TrollStore)
2. Download the IPA file from the table below
3. Open IPA in TrollStore

- The following IPA's binary and Plugins are fake signed with their original entitlements
- It does not include any fixes for WhatsApp, so `IT WILL CRASH` if not used in TrollStore or not signed with proper certificate and entitlements.

| Application | Bundle | Version | Watusi 3 | Stalky | OnlineNotify |
| ------------------ |:---------:|:------:|:------:|:------:|:------:|
| [WhatsApp][original-nofix] | net.whatsapp.WhatsApp | 23.15.0 | 1.1.66 | 4.1.22 |  3.4.3 |
| [WhatsApp Business][business-nofix] | net.whatsapp.WhatsAppSMB | 23.14 .82 | 1.1.66 | 4.1.22 |  3.4.3 |


```Stalky and OnlineNotify tweaks are disabled by default and can be enabled from inside Watusi Settings.```
</details>

<details>
<summary><h2>Sideloading as linked device (Push Notifictions + iCloud Backup)</h2></summary>

Since WhatsApp added the option to link a device on mobile, you can now use the original WhatsApp from the AppStore and install Watusi IPA as a duplicate and link your original WhatsApp to it.

* Install and activate original WhatsApp from the AppStore
* Download and install [duplicated Watusi IPA](#sideloading-no-jailbreak) from the table above.
* It is recommended to enable Watusi's `Local Notifications` feature on your duplicate to keep the app active while linking.
  * Open duplicated Watusi, from the welcome screen, tap 3 times on the animated image and select `Watusi` preferences, go to the `Notifications` section and activate `Enable Local Notifications`, and set it to `Location`.
* Move back to the welcome screen, tap `Agree and Continue`, and click on `Link this device` to get the QR Code. Screenshot this code and send it to another device.
* Switch to your original WhatsApp
  * Go to `Settings > Linked Devices > Link a Device`
  * Scan the QR code from your other device and wait for it to link and load your chats

You will now receive notifications from your original WhatsApp and use the duplicated app with Watusi and other tweaks.

You can also remove the original WhatsApp from your home screen so you only use the duplicated app.

Optionally, you can create automation from the Shortcuts app to have your duplicated app open automatically when opening the original WhatsApp (especially from notifications).

Make sure to open the original WhatsApp from time to time to keep chats in sync and backed up to iCloud.

</details>

## FAQ
* If you receive "Please sign in with app-specific password" error, that's because you have 2-factor authentication enabled for your Apple ID. You have to go to Apple's website https://appleid.apple.com, log in with your account and create an app-specific password to use as your Apple ID password.
* Signing the app with a non-developer account will have it expire in 7 days, but AltStore automates re-signing as long as it is connected to your PC.
* The app will not receive Push Notifications and you won't be able to use iCloud features (Except for TrollStore on supported devices).
