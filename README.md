<p align="center">
  <img src="assets/somdroid-icon.png" width="112" alt="SomDroid icon">
</p>

<h1 align="center">SomDroid</h1>

<p align="center">Free bulk SMS for Android. One message, your whole list, one SMS at a time.</p>

<p align="center"><a href="https://github.com/JOOGDHEERE69/somdroid-releases/releases/latest"><b>Download the latest APK</b></a></p>

---

## What it does

You import a list of numbers from a CSV, TXT or Excel file, write one message and pick SIM 1 or SIM 2. SomDroid then sends the SMS one by one at the interval you set, now or at a time you schedule, and shows live delivery for every number.

- **No message is wasted or sent twice.** It waits during calls and when there's no signal. It pauses itself if several messages fail in a row, for example when the balance runs out, and alerts you in Somali and English.
- **Live delivery tracking**, with one-tap resend to the numbers that failed.
- **Free, with no account.** SomDroid has no internet permission, so your numbers never leave your phone.
- Available in Soomaali and English, for Android 8.0 and newer.

## Install

1. Open the [latest release](https://github.com/JOOGDHEERE69/somdroid-releases/releases/latest) on your phone and download `SomDroid-vX.Y.Z.apk`.
2. Open the file. If Android asks, allow **Install unknown apps** for your browser or file manager.
3. Open SomDroid and allow **SMS**, **Phone** and **Notifications**. If Android says *Restricted setting*, go to **App info**, tap **⋮** and choose **Allow restricted settings**.
4. After about 30 messages, Android may ask whether SomDroid can send many SMS. Choose **Always allow**.

To update, install the newer APK over the old one. Your history is kept.

## Check your download

Every release lists the APK's SHA-256. On Windows:

```powershell
Get-FileHash .\SomDroid-v1.0.0.apk -Algorithm SHA256
```

The value should match the one on the release page.

---

This repository only hosts the app downloads.
