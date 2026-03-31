# Manual CD Player Widget

A hilarious retro-style CD player widget that requires users to manually spin the disc to play audio - just like being a real DJ!

**Live Demo:** https://daviddzhou.github.io/manual-cd-player/

## Features

- **Manual Spin Control**: Drag the CD to spin it like a turntable
- **Coast Mode Toggle**: Switch between momentum physics (realistic) and instant stop
- **RPM Controls**: Adjustable min/max RPM thresholds for audio playback
- **Real-time Status**: Displays current RPM and track progress
- **Windows XP Aesthetic**: Retro styling matching the memelord.com theme
- **Variable Speed Audio**: Playback speed adjusts based on how fast you spin
- **Touch Support**: Works on both desktop and mobile devices

## How to Use

1. **Open** `index.html` in any modern web browser
2. **Drag** the CD to spin it
3. **Audio plays** when RPM exceeds the minimum threshold
4. **Spin faster** to increase playback speed
5. **Toggle Coast Mode** for realistic momentum physics
6. **Adjust sliders** to customize min/max RPM thresholds

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- No external dependencies (except the audio file)
- Uses Web Audio API for playback rate control
- CSS animations for smooth rotation
- Responsive design with touch support

## Integration

To integrate into memelord.com/docs:

1. Copy the CD player container HTML into your page
2. Include the CSS styles
3. Include the JavaScript class
4. Replace the audio source with your actual audio file
5. Optionally replace the CSS-generated CD with the actual CD image asset

## License

MIT License - Feel free to use and modify for your projects!

## Credits

- Audio: Royalty-free piano jazz from Pixabay
- Design: Windows XP aesthetic inspired by memelord.com
- CD Design: Based on the "Is it live or is it Memorex?" meme
