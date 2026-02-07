# ⏰ Zen Student Clock

A beautiful, distraction-free productivity timer designed specifically for students and focus enthusiasts. Combines the power of the Pomodoro Technique with versatile timing tools in a calming, minimalist interface.

## 🌟 Features

### 🍅 **Smart Pomodoro Timer**
- Structured 25-minute focus sessions with 5-minute breaks
- **Pause & Confirm**: Timer pauses after each phase and asks for your confirmation before switching
- Built-in browser notifications and audio chimes
- Customizable focus and break durations

### ⏱️ **Versatile Time Management**
- **Countdown Timer**: Set custom timers for any duration (hours, minutes, seconds)
- **Stopwatch**: Track time spent on tasks with pause/resume functionality
- **Deadline Tracker**: Count down to specific times (exams, submissions, etc.)
- Pause/resume support across all modes

### 🎨 **13 Beautiful Themes**
**Light Themes:**
- 🌿 Zen Green (Default)
- 🌊 Calm Blue
- 📜 Paper Beige
- ⚪ Slate Grey
- 🌸 Lavender Dream
- 🍑 Sunset Peach
- 🌱 Mint Fresh

**Dark Themes:**
- 🌙 Classic Dark
- 🔮 Deep Purple Night
- 🌲 Forest Night
- 🌊 Ocean Deep
- 🔥 Midnight Amber
- 🌺 Cherry Blossom Dark

### ✨ **Zen Focus Experience**
- **Auto-Hide UI**: Controls fade after 3 seconds of inactivity for distraction-free focus
- Large, easy-to-read time display
- Full-screen mode support
- Optional seconds display
- Smooth animations and transitions
- Theme persistence (saves your preference)

## 🚀 Quick Start

### Option 1: Direct Use
1. Download `zen-student-clock.html`
2. Open it in any modern web browser
3. Bookmark it for quick access
4. That's it! No installation needed.

### Option 2: Local Development
```bash
# Clone or download the file
# Open in your browser
open zen-student-clock.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📖 How to Use

### Pomodoro Mode
1. Click the **Pomodoro** tab
2. Set your focus duration (default: 25 min) and break duration (default: 5 min)
3. Click **Start Focus**
4. When the timer completes, a dialog will appear asking if you want to start your break
5. Click **Yes, Continue** to proceed or **Stop** to end the session

### Timer Mode
1. Click the **Timer** tab
2. Enter hours, minutes, and seconds
3. Click **Start Timer** to begin
4. Use **Pause** to temporarily stop, **Resume** to continue
5. Click **Reset** to start over

### Stopwatch Mode
1. Click the **Stopwatch** tab
2. Click **Start Stopwatch** to begin tracking time
3. Use **Pause** to stop temporarily
4. Click **Reset** to clear

### Deadline Mode
1. Click the **Deadline** tab
2. Select a target time
3. Click **Set Target**
4. Watch the countdown to your deadline

## 🎯 Perfect For

- 📚 **Students** preparing for exams and managing study sessions
- 💼 **Remote Workers** using the Pomodoro Technique
- 🧠 **People with ADHD** who benefit from timed focus periods
- ✍️ **Writers & Creatives** working on timed projects
- 🎓 **Anyone** seeking better time management and focus

## 🔔 Browser Notifications

On first use, the browser will ask for notification permission. Click **Allow** to receive:
- Focus session completion alerts
- Break reminders
- Timer/deadline notifications

**Note**: Notifications work even when the tab is in the background!

## ⌨️ Keyboard & Interaction

- **Mouse Movement**: Shows hidden controls
- **Full Screen**: Toggle distraction-free mode
- **Auto-Hide**: UI fades after 3 seconds of inactivity
- **Theme Selection**: Persists across sessions

## 🛠️ Technical Details

- **Zero Dependencies**: Pure HTML, CSS, and JavaScript
- **Offline Ready**: Works without internet connection
- **Privacy First**: No data collection, no tracking, no cookies
- **Browser Notifications API**: For alerts
- **Web Audio API**: For chime sounds (no external audio files)
- **localStorage**: For theme preference only

### Browser Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ Any modern browser with ES6 support

## 🎨 Customization

Want to modify the themes? Edit the CSS variables in the `:root` and `[data-theme]` sections:

```css
[data-theme="your-theme"] {
    --bg-color: #your-background;
    --text-main: #your-text-color;
    --accent: #your-accent-color;
    /* ... */
}
```

## 🐛 Known Limitations

- Timer/Pomodoro persistence: Timers reset on page refresh (by design for simplicity)
- Audio requires user interaction: First click enables audio context (browser security requirement)
- Mobile notifications may vary by browser and OS

## 📝 License

MIT License - Free to use, modify, and distribute.

## 🤝 Contributing

This is a single-file project for simplicity. Feel free to:
- Fork and customize for your needs
- Share improvements
- Report issues
- Suggest new themes or features

## 💡 Tips for Best Results

1. **Allow Notifications**: Get alerts even when browsing other tabs
2. **Use Full Screen**: Eliminate all distractions during focus time
3. **Find Your Theme**: Different colors affect mood - experiment!
4. **Pomodoro Technique**: 25min work + 5min break is scientifically proven effective
5. **Bookmark It**: Add to bookmarks bar for instant access

## 🌟 Why Zen Student Clock?

Unlike bloated productivity apps:
- ✅ No account required
- ✅ No subscriptions or paywalls
- ✅ No data collection
- ✅ No internet required (after download)
- ✅ No installation
- ✅ Completely free forever

Just pure, focused productivity in a beautiful interface.

---

**Made with ❤️ for students everywhere**

*Stay focused. Stay productive. Stay zen.* 🧘‍♂️
