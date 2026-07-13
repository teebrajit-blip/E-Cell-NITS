# Digital Clock - Multiple Time Zones

A beautiful, responsive web application that displays the current time across different time zones around the world.

## Features

✨ **Key Features:**
- **Real-time Clock Updates**: Updates every second to show accurate time
- **Multiple Time Zones**: Displays time in 8 major cities by default
- **Add Custom Time Zones**: Dropdown to add any timezone from the list
- **12/24 Hour Toggle**: Switch between 12-hour and 24-hour time format
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Beautiful UI**: Modern gradient design with smooth animations
- **Date Display**: Shows the full date along with the time

## Default Time Zones

The clock displays time in these major cities:
1. 🗽 New York (America/New_York)
2. 🇬🇧 London (Europe/London)
3. 🇫🇷 Paris (Europe/Paris)
4. 🇦🇪 Dubai (Asia/Dubai)
5. 🇮🇳 India IST (Asia/Kolkata)
6. 🇯🇵 Tokyo (Asia/Tokyo)
7. 🇦🇺 Sydney (Australia/Sydney)
8. 🌴 Los Angeles (America/Los_Angeles)

## How to Use

1. **Open the file**: Simply open `digital-clock.html` in any modern web browser
2. **View Times**: All clocks update automatically every second
3. **Toggle Format**: Click "Toggle 12/24 Hour" button to switch time formats
4. **Add Timezone**: Select from dropdown to add custom time zones
5. **Remove Timezone**: Click "Remove" on custom added zones to delete them

## Supported Time Zones

The application supports 24+ time zones including:
- UTC
- Americas: New York, Chicago, Denver, Los Angeles, Anchorage, Honolulu
- Europe: London, Paris, Berlin, Amsterdam, Madrid, Rome, Athens
- Asia: Dubai, Kolkata, Bangkok, Singapore, Hong Kong, Tokyo
- Oceania: Sydney, Melbourne, Brisbane, Auckland
- And more!

## Technical Details

- **Language**: HTML5, CSS3, JavaScript (Vanilla)
- **No Dependencies**: Pure client-side code, no external libraries required
- **Browser Compatible**: Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- **Performance**: Lightweight and fast, minimal resource usage

## File Structure

```
E-Cell-NITS/
├── digital-clock.html   (Main application file)
└── CLOCK-README.md      (This file)
```

## How It Works

1. **Time Calculation**: Uses JavaScript's `Intl.DateTimeFormat` API to get accurate time in different time zones
2. **Real-time Updates**: Uses `setInterval()` to update the display every second
3. **Format Toggle**: Converts between 12-hour (AM/PM) and 24-hour formats
4. **Dynamic Addition**: Allows users to add custom time zones on the fly

## Customization

You can easily customize the clock by:
- **Changing Default Time Zones**: Modify the `timeZones` array in the script
- **Styling**: Update the CSS gradients and colors
- **Adding Features**: Extend functionality like alarms, world map, etc.

## Browser Support

- ✅ Google Chrome 24+
- ✅ Mozilla Firefox 29+
- ✅ Safari 9.1+
- ✅ Microsoft Edge (All versions)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## License

Free to use and modify for personal and commercial projects.

## Author

Created for E-Cell NITS

---

**Enjoy tracking time across the globe! 🌍⏰**