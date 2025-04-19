# Guts Round Live Scoreboard

A dynamic, interactive scoreboard designed for Guts Round mathematics competitions. This web-based application provides real-time score tracking with a clean, professional interface.

## Features

### Editor Mode
- **Team Management**
  - Add teams with custom names
  - Update scores manually with +/- adjustments
  - Prevent duplicate team names
  - Real-time score updates

### Timer Functions
- **Countdown Timer**
  - Set custom duration in minutes
  - Start/Stop/Reset functionality
  - Clear display of remaining time
  - Continues running in presentation mode

### Presentation Mode
- **Live Leaderboard**
  - Full-screen display optimized for projectors
  - Teams sorted by score in real-time
  - Rank numbers displayed for each team
  - Quick-score feature: click any team to add 1 point
  - Visual feedback on score updates
  - Centered 75% width display for optimal visibility

### Visual Design
- **Clean**
  - Navy Blue (#002147)
  - Gold (#FFD700)
  - Red (#C8102E)
  - Professional animations and transitions
  - Responsive layout

## How to Use

1. **Setup**
   - Open `index.html` in any modern web browser
   - No installation or dependencies required

2. **Adding Teams**
   - Enter team name in the "Add Team" section
   - Click "Add" or press Enter
   - Teams appear in both editor list and leaderboard

3. **Managing Scores**
   - In Editor Mode:
     - Use the +/- input field next to each team
     - Click "Update" to apply score changes
   - In Presentation Mode:
     - Simply click on any team to add 1 point
     - Leaderboard updates automatically

4. **Using the Timer**
   - Enter duration in minutes
   - Use Start/Stop/Reset buttons to control
   - Timer visible in both modes

5. **Switching Modes**
   - Click "Switch to Presentation Mode" for full-screen display
   - Click "Switch to Editor Mode" to return to management view
   - Use ESC key to exit full-screen

## Technical Details

- Pure HTML/CSS/JavaScript implementation
- No external dependencies
- Responsive design works on all screen sizes
- Local storage not implemented (scores reset on page refresh)

## Browser Support

Works in all modern browsers that support:
- CSS Grid/Flexbox
- ES6 JavaScript
- Fullscreen API

## License

This project is open source and available for use.

## Contributing

Feel free to submit issues and enhancement requests.
