# Privacy Policy for SatPass Planner

Last updated: November 22, 2026

SatPass Planner predicts when satellites pass over you. It is for radio amateurs and satellite observers, on iPhone, iPad and Mac. On your device, its name is SatPass. This policy applies to the app on all three platforms.

## Summary

- SatPass collects no data for the developer. SatPass has no analytics, no ads and no account, and it does not track you.
- SatPass calculates the pass predictions on your device. Your location does not go to the developer.
- SatPass downloads public satellite data from the data server of the developer. These requests contain no personal data. The sections below give the details.

## The connections that SatPass makes

**The SatPass data server.** SatPass downloads orbit data and radio transmitter data from `satpass-data.pages.dev`. The orbit data comes from CelesTrak, which uses data from USSPACECOM. The transmitter data comes from SatNOGS DB. The developer operates this server on Cloudflare Pages. The requests ask only for public data files and contain no data about you. Cloudflare uses the IP address of your device to send the files, as all web hosts do. The [Cloudflare privacy policy](https://www.cloudflare.com/privacypolicy/) applies. The developer does not receive or keep request logs.

**Apple Maps, when you add or edit a location.** SatPass sends the coordinates of that location to Apple to find its time zone. The [Apple privacy policy](https://www.apple.com/legal/privacy/) applies.

**iCloud.** iCloud syncs your saved locations, favorite satellites and alert rules between your devices. This data is in your private iCloud database. The developer cannot read it.

**Data sources that you add.** You can add an orbit data source from a web address. SatPass then downloads the data directly from that address.

**Your radio and rotator.** For radio or rotator control, SatPass connects only to the rigctld or rotctld address that you type. This address is usually a computer on your network. On iPhone and iPad, the system first asks for Local Network permission.

**SatPass makes no other connections.**

## Your location

- SatPass uses your location to calculate which satellites pass over you, and when.
- You can type a Maidenhead grid square or coordinates. SatPass then does not need location access.
- An approximate location is sufficient. SatPass works when Precise Location is off.
- SatPass uses your location on your device. It sends the location only to Apple, for the time zone search above.

## Camera and motion sensors

- Point & Track, on iPhone and iPad, shows the live camera picture under the satellite path. SatPass shows the picture on the screen only. SatPass does not record, store or send it.
- The system asks for camera access the first time. Without camera access, Point & Track shows the satellite path on a black background.
- Point & Track reads the motion sensors and the compass to find the direction of the device. This occurs on your device, and SatPass sends nothing.

## Notifications

The system on your device schedules the pass alerts. The alerts do not go through a server.

## The data that SatPass stores

- **On your device:** the selected location, the display settings, the radio settings and the downloaded satellite data. SatPass also keeps a copy of your next passes for the widgets.
- **In your private iCloud database,** if iCloud is on: the saved locations, the favorite satellites and the alert rules.

## Purchases

The App Store sells SatPass Pro. Apple processes the payments. The developer does not receive your payment details. SatPass checks your purchases with Apple, on your device.

## Apple analytics

The App Store supplies purchases and updates. You can choose to share analytics with app developers. If you do, Apple can send crash reports and total usage numbers to the developer. You can stop this in the Apple settings:

- iPhone and iPad: Settings › Privacy & Security › Analytics & Improvements.
- Mac: System Settings › Privacy & Security › Analytics & Improvements.

## Delete your data

- When you delete a location, a favorite or an alert rule in SatPass, SatPass removes it from your device and from your iCloud database.
- When you delete the app, the system removes its data from the device.
- To remove the SatPass data from iCloud on all devices, use these settings:
  - iPhone and iPad: Settings › your name › iCloud › Manage Account Storage.
  - Mac: System Settings › your name › iCloud › Manage.

## Children

SatPass collects no data from any person. This includes children under 13.

## Changes to this policy

The developer puts each change on this page, with a new date.

## Contact

For questions about this policy, open an issue at https://github.com/Tuareg0xFFFF/SatPass-PUB-/issues.
