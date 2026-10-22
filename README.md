# LUMIS Preview (Android)

Release builds of the **LUMIS Preview** app, the Android container that lets you experience a Shopify store the way its customers would: browse products, chat with the AI shopping assistant, add to cart and check out.

This repository contains release builds only. It is not the branded store app your customers download.

## Install
1. Download `lumis-preview.apk` from the [latest release](https://github.com/naixu9x/lumis-releases/releases/latest) on an Android phone.
2. Allow installs from your browser or file manager when Android asks (normal for apps installed outside Google Play).
3. Open the app and scan the preview QR code shown in LUMIS (Shopify Admin > Mobile App Settings).

Without a camera (for example an emulator), open the link `lumis://store?id=<your-store>.myshopify.com` on the device.

## Verify the download
Each release lists the SHA-256 of the APK. Releases are signed with a certificate whose SHA-256 fingerprint is:

```
71:89:DF:76:9C:4B:71:B0:FA:EF:8C:76:8B:58:57:DD:D7:8D:90:A2:6F:71:26:05:63:59:A8:5E:49:AB:BD:B5
```

## Notes
- Preview builds are for evaluation. Android only for now.
- The app talks to the LUMIS service; it needs internet access.
