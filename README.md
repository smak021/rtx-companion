# RTX Companion

RTX Companion is a lightweight, offline Android companion app for the Apache
RTX 300 cluster. It is designed to reduce phone heat and battery use by avoiding
map mirroring, continuous screen-on operation, cloud services, analytics, and
unnecessary background work.

Connect it to your bike once, and it will reconnect automatically whenever the
bike is turned on. Start a route using Google Maps on your phone to send live
turn-by-turn guidance to the cluster—even while the phone is locked.

> **Use at your own risk.** This project is independent and is not affiliated
> with or endorsed by TVS Motor Company or Google.

## Requirements

- TVS Apache RTX
- Android 16 phone
- Bluetooth and notification permission
- Notification access for Google Maps guidance

## Install

1. Download the APK from **Releases**.
2. Install and open RTX Companion.
3. Tap **Connect to RTX** and select the bike.
4. Allow the requested Bluetooth and notification permissions.
5. Allow notification access when prompted for navigation.

The app reconnects automatically when the bike is turned on. Do not **Force
stop** the app; Android disables automatic background connection until it is
opened again.

## Navigation

1. Connect RTX Companion to the bike.

   _Skip this step if already connected once. You do not need to open RTX
   Companion again—just open Google Maps and start navigation._

2. Start a route in Google Maps.
3. Lock the phone if desired. Turn guidance should appear on the cluster.

On Samsung phones, keep **Power saving turned off while navigating**. Power
saving can delay Google Maps updates when the phone is locked. Also keep Google
Maps and RTX Companion out of **Sleeping apps** and **Deep sleeping apps**.

## Switching to TVS Connect

Open RTX Companion and tap **Disable Companion** before connecting with the
official TVS Connect app. Activate RTX Companion again when you want to use it.

## Privacy and safety

- Works locally without an account, ads, analytics, or Internet permission.
- Does not modify motorcycle firmware or perform ECU, diagnostic, immobilizer,
  or vehicle-control operations.
- Navigation information may be delayed or incorrect. Follow road signs and do
  not operate the phone while riding.
- Compatibility outside the tested Galaxy S23 and Apache RTX is not guaranteed.

## Safety boundary

RTX Companion is limited to displaying supported bike data and sending
phone-side navigation and status information to the paired cluster.

It does not access or modify the ECU, firmware, diagnostics, immobilizer,
engine, lights, horn, locks, braking, or other vehicle-control systems.

## To do

- Call notifications and call controls on the cluster.
- Music information and playback controls on the cluster.
