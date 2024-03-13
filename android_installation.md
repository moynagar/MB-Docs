# MB Smart Android Installation Guide

## Requirements:

- Android version 5.0 and above
- No other device owner present in the device
- Storage must not be completely full
- Charging port must work (unless the idea is to install via QR code)
- For Android version 14, signing out of all accounts in settings is a prerequisite for installation, this is done by going into _Settings_ |> _Passwords and accounts_ and removing each one. This will mean that the user needs to sign in to their accounts once again after installation.

## Brand Specific Instructions:

### Samsung

- _Secure Folder_ causes issues with installation, where the app is not able to be installed correctly onto the device, thus uninstalling it from settings is necessary before installing the filter by entering into _Secure Folder_ |> _Settings_ and pressing uninstall.
- _Secondary Users_ such as guest user, multiple users or dual messenger will cause the filter installation to fail, so they need to be removed as well.

### Xiaomi

- It is required to turn off _MIUI Optimization_ in developer options and _Install via USB_ in the USB debugging section

### Other Chinese Brands

- Like with Xiaomi, _Install via USB_ needs to be enabled in Developer Options
- Some additional permissions might be required for background apps, so set MB Smart to have them allowed

## Step by Step installation:

- Go into _Settings_ |> _About phone_[^1] |> _Software Information_.
- Scroll down to _Build number_ and tap until a notice appears informing that developer options have been enabled.
- Go back to the main settings menu, where a new option called _Developer options_.
- Go into _Developer options_, scroll down to _USB debugging_ and switch it on.
- On your computer, open the installer, either [standalone](https://installer.mbsmart.net/MB_Installer.exe) or through TAG Hub and connect the device into the computer via USB.
- Accept the connection on the device, the installer should then go through several screens and then complete, showing a green screen[^2].
- On the device, the application should have installed and started on it's own, accept the terms and conditions.
- Continue to account creation, filling in the user's details, the office linkcode, and a pin which will be used to request support.
- Once account creation is done, you will be prompted to give permissions to the MB Smart app.
- A payment screen will be presented, after which you will proceed to configure the device on the portal, optionally.

## Transferring to a new device while keeping the same account:

- Uninstall filter from the old device. If this is not possible it will not cause issues.
- On the [portal](https://portal.mbsmartservices.com), after filter is set to off on the Main tab, a RecoveryID will be generated. This can be found on the User list, on the last row. ![You can find it on the rightmost column of the User list](./RecoveryID.png)
- Install on the new device normally up until getting a green screen on the installer, and proceed into the device.
- Instead of creating a new account on the device, select Recover and insert the RecoveryID generated, including the colon and email, the format should be as follows <#ID:email\>
> [!Note]
> Most keyboards insert spaces after punctuation, so be mindful of this and make sure there are no spaces around or in between the RecoveryID parts
- Set up permissions as you would do any other installation. The filter should now be completely installed and configured the same as the original account was.
> [!Important]
> A new ID will be generated for the new device, so if there is need to work on the portal for the account make sure to use the appropiate one.

## Device Owner

> [!Note]
> WIP Please Ignore 
---
[^1]: Sometimes called by other names, if there is difficulty finding this section, just search for build number in the Settings app.
[^2]: Sometimes we encounter errors, refer to the Troubleshooting section for more info.
