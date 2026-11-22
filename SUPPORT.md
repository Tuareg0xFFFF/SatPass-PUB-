# SatPass Planner Support

SatPass Planner predicts satellite passes on iPhone, iPad and Mac. It also gives Doppler tuning and radio control for radio amateurs. On your device, its name is SatPass. This page tells you how to find help, report a problem or ask for a feature.

Last updated: November 22, 2026

## Help

Open an issue on GitHub:

**https://github.com/Tuareg0xFFFF/SatPass-PUB-/issues**

## Checks to do before you open an issue

1. **The passes are not correct, or some passes are not shown.**
   - Check your location in Settings. Also check its time zone.
   - Check the minimum elevation in Settings. SatPass does not show passes with a lower maximum elevation.
   - Look at **Orbit data** at the top of the pass list. If it shows Stale or Expired, connect to the internet and select Refresh.
2. **The alerts do not arrive.**
   - Make sure that notifications for SatPass are on in the system Settings.
   - Make sure that alerts are on for this device in Settings › Alerts. Each device has its own switch. Thus your iPhone, iPad and Mac do not all give an alert for the same pass.
3. **Radio or rotator control does not connect.**
   - Make sure that rigctld or rotctld runs and that this device can connect to it. Try the address and the port from a different computer.
   - On iPhone and iPad, make sure that Local Network access for SatPass is on in the system Settings › Privacy & Security.
4. Make sure that you have the latest version of SatPass from the App Store.

## Report a problem

Include this data:

- **The SatPass version:** Settings › Acknowledgements, at the bottom.
- **The device and the system:** the device model, and the iOS, iPadOS or macOS version.
- **The satellite and the pass,** for a problem with a prediction: the name or NORAD number of the satellite, and the date and time.
- **For radio control:** the radio model, the rotator model and the Hamlib version (`rigctld --version`).
- **The steps that cause the problem,** the result that you expected and the result that you saw.
- **Screenshots or a screen video,** if they help.

Do **not** put your exact home location or your network addresses in a public issue. A nearby town or a 4-character grid square is sufficient.

## Frequently asked questions

**The accuracy of the predictions.**
SatPass uses the standard SGP4 orbit model. The orbit data is usually less than one day old. Each pass shows a ± time error, and this error increases as the data becomes older. With new data, the times are usually correct to a few seconds.

**Offline use.**
SatPass works offline. It predicts on your device from the last orbit data that it downloaded. It also shows the age of that data.

**The radios that SatPass can control.**
SatPass can control all radios and rotators that Hamlib supports. It connects to rigctld and rotctld on a computer on your network. Radio control is part of SatPass Pro.

**The price of Pro.**
SatPass Pro costs US $14.99 each year, or $49.99 one time. Both options are for iPhone, iPad and Mac. Both options work with Family Sharing.

**The sources of the data.**
The orbit data comes from CelesTrak, which uses data from USSPACECOM. The radio transmitter data comes from SatNOGS DB (CC BY-SA 4.0). Refer to Settings › Acknowledgements.

**Your data.**
SatPass sends no personal data to the developer. Refer to the [privacy policy](PRIVACY.md).

## Feature requests

Open an issue. Start its title with "Feature request:". Then tell what you want to do.

## Privacy

Refer to [PRIVACY.md](PRIVACY.md) for the privacy policy.
