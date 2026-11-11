# Privacy Policy for SatPass Planner

Last updated: November 10, 2026

SatPass Planner (shown as SatPass on your device) predicts when satellites pass over you, for radio amateurs and satellite watchers, on iPhone, iPad and Mac. This policy covers the app on all three.

## The short version

- SatPass collects nothing for the developer. There are no analytics, no tracking, no ads, and no SatPass account.
- Pass predictions are calculated on your device. Your location never reaches the developer.
- SatPass downloads public satellite data from the developer's data server. Those requests carry no personal information. Details below.

## What SatPass connects to

**The SatPass data server.** Orbit data (from CelesTrak, derived from USSPACECOM data) and radio transmitter data (from SatNOGS DB) are downloaded from `satpass-data.pages.dev`. The developer runs this server on Cloudflare Pages. The requests ask only for public data files and contain nothing about you. Like any web host, Cloudflare handles your device's IP address to deliver the files, under [Cloudflare's privacy policy](https://www.cloudflare.com/privacypolicy/). The developer does not receive or keep request logs.

**Apple Maps, when you add or edit a location.** SatPass sends that location's coordinates to Apple to look up its time zone, under [Apple's privacy policy](https://www.apple.com/legal/privacy/).

**iCloud.** Your saved locations, favorite satellites and alert rules sync between your devices through iCloud, in your private iCloud database. The developer can't read it.

**Data sources you add.** If you add your own orbit data source by web address, SatPass downloads it straight from that address.

**Your radio and rotator.** If you use radio or rotator control, SatPass connects only to the rigctld or rotctld address you enter, usually a computer on your own network. On iPhone and iPad, the system asks for Local Network permission first.

**Nothing else.**

## Your location

- SatPass uses your location to work out which satellites pass over you, and when. You can enter a Maidenhead grid square or coordinates instead of allowing location access.
- Approximate location is enough, so SatPass works with Precise Location turned off.
- Your location is used on your device, and sent only to Apple for the time-zone lookup above.

## Notifications

Pass alerts are scheduled on your device by the system. They don't go through any server.

## What is stored, and where

- **On your device:** the selected location, display settings, radio settings and the downloaded satellite data. A copy of your next passes is also kept for the widgets.
- **In your private iCloud database,** if iCloud is on: saved locations, favorite satellites and alert rules.

## Purchases

SatPass Pro is sold through the App Store. Apple processes payments, and the developer never receives your payment details. SatPass checks what you have bought with Apple, on your device.

## Apple devices

The App Store handles purchases and updates. If you have chosen to share analytics with app developers, Apple may pass the developer crash reports and aggregate usage figures. That is an Apple setting you can turn off: Settings › Privacy & Security › Analytics & Improvements on iPhone and iPad, and System Settings › Privacy & Security › Analytics & Improvements on Mac.

## Deleting your data

- Deleting a location, favorite or alert rule in SatPass removes it from your device and from your iCloud database.
- Deleting the app removes its data from the device.
- To remove SatPass's iCloud data from every device:
  - iPhone and iPad: Settings › your name › iCloud › Manage Account Storage.
  - Mac: System Settings › your name › iCloud › Manage.

## Children's privacy

SatPass collects no data from anyone, including children under 13.

## Changes to this policy

Updates are posted on this page with a new date.

## Contact

Questions about this policy: open an issue at https://github.com/Tuareg0xFFFF/SatPass-PUB-/issues.
