---
layout: page
title: FAQ
include_in_header: true
---

# Frequently Asked Questions

## Q: What kind of second factor auths are supported?
**A:** Codes implements [Time-based One-time Password algorithm](https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm). This allows Codes to support second factor auth for most popular web services, like Google, Facebook, Microsoft, Twitter and so on.

## Q: How is my data stored?
**A:** By default Codes store data localy in on-device Apple Keychain, data is encrypted and never leaves your device. Optionally you can choose to store selected accounts in iCloud keychain, this will enable access to this data from multiple devices.

## Q: How can I control the storage option for given account?
**A:** Long press on account and choose "Store in iCloud" or "Store on Device" options from the menu.

## Q: What happens when I choose "Store on Device" option?
**A:** The account data will be copied to the device, all other devices will loose access to this account.

## Q: I've selected "Store in iCloud" option but my data is not available on other devices, what should I do?
**A:** Codes uses iCloud Keychain, which means it should be enebled on your devices. iCloud keychain syncs automatically, there is no way to force it or check sync status. Usually data appears on other devices within seconds, but sometimes it can take longer. Use [official troubleshooting guide](https://support.apple.com/en-us/HT203783) if needed.

## Q: What happens when I delete account which is stored in iCloid?
**A:** The account data will be deleted from iCloud Keychain and all devices.

## Q: Can I export or share my data from Codes?
**A:** Yes, long press on account and choose "Show QR Code". Scan this QR code in Codes or other OTP app.

## Q: Can I restrict QR codes sharing?
**A:** Yes, you can enable/disable QR code sharing on per account basis. Choose the desired behaviour in Settings, new settings options affects only accounts added after the change was made.

## Q: Can I edit account icon in Codes?
**A:** No. Icon is set automatically based on key words in account name. Icons are provided by [Font Awesome](https://fontawesome.com/icons?d=gallery&s=brands&m=free).

## Q: Do you support opening otpauth:// URLs?
No, but codes can detect otpauth:// URL in clipboard and autofill Manual Add dialog.

## Q: Why Codes is free?
It is hard enough to make people to use 2-FA in the first place, we don't need another obstacle. All competitors apps are free as well. If you want to support future development you can use Tip Jar.

## Q: Is there a Privacy Policy
**A:** [Yes.](/privacypolicy)

## Q: How can I contact you?
**A:** Email us at [info@ameba.co](mailto:info@ameba.co)