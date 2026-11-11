# SatPass Planner Support

SatPass Planner (shown as SatPass on your device) predicts satellite passes on iPhone, iPad and Mac, with Doppler tuning and radio control for radio amateurs. Here is how to get help, report a problem, or ask for a feature.

Last updated: November 10, 2026

## Getting help

Open an issue on GitHub:

**https://github.com/Tuareg0xFFFF/SatPass-PUB-/issues**

## Before you open an issue

1. **Passes look wrong or are missing.**
   - Check your location in Settings, including its time zone.
   - Check the minimum elevation in Settings: passes peaking lower are hidden.
   - Look at **Orbit data** at the top of the pass list. If it says Stale or Expired, tap Refresh while online.
2. **Alerts don't arrive.**
   - Check that notifications are on for SatPass in the system Settings.
   - Check that alerts are on for this device in Settings › Alerts. Each device has its own switch, so your iPhone, iPad and Mac don't all alert for the same pass.
3. **Radio or rotator control doesn't connect.**
   - Check that rigctld or rotctld is running and reachable from this device. Try the address and port from another computer.
   - On iPhone and iPad, check that Local Network access is on for SatPass in the system Settings › Privacy & Security.
4. Make sure you have the latest SatPass from the App Store.

## Reporting a bug

Please include:

- **SatPass version:** Settings › Acknowledgements, at the bottom.
- **Device and system:** the iOS, iPadOS or macOS version and the device model.
- **The satellite and the pass,** if it's about a prediction: the satellite's name or NORAD number, and the date and time.
- **For radio control:** the radio and rotator models, and your Hamlib version (`rigctld --version`).
- **Steps to reproduce,** what you expected, and what happened.
- **Screenshots or a screen recording,** if they help.

Do **not** post your exact home location or your network addresses in a public issue. A nearby town or a 4-character grid square is enough.

## Frequently asked questions

**How accurate are the predictions?**
SatPass uses the standard SGP4 orbit model with orbit data that is usually less than a day old. Each pass shows a ± timing estimate that grows as the data ages. Times are typically good to a few seconds when the data is fresh.

**Does it work offline?**
Yes. SatPass predicts on your device from the last orbit data it downloaded, and shows how old that data is.

**Which radios can it control?**
Any radio or rotator that Hamlib supports, through rigctld and rotctld running on a computer on your network. Radio control is part of SatPass Pro.

**What does Pro cost?**
US $14.99 a year, or $49.99 once. Both cover iPhone, iPad and Mac and can be shared with Family Sharing.

**Where does the data come from?**
Orbit data from CelesTrak, derived from USSPACECOM data. Radio transmitter data from SatNOGS DB (CC BY-SA 4.0). See Settings › Acknowledgements.

**Does SatPass send my data anywhere?**
No personal data goes to the developer. See [PRIVACY.md](PRIVACY.md).

## Feature requests

Open an issue whose title starts with "Feature request:", and describe what you are trying to do.

## Privacy

See [PRIVACY.md](PRIVACY.md) for the privacy policy.
