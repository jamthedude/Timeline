# Timeline 📅

A beautiful, interactive web application for visualizing and managing your life events on an interactive timeline.

## Features

✨ **Interactive Timeline Visualization**
- Explore your life events on a zoomable, pannable timeline powered by [Vis.js](https://visjs.org/)
- Navigate through decades of memories with smooth animations
- Auto-fit view to see all events at once

📸 **Rich Event Details**
- Add titles, descriptions, dates, and times to each memory
- Attach multiple images to events
- Tag events for easy filtering and organization
- Mark minor events to declutter your view

🔄 **Recurring Events**
- Create series of recurring events (daily, weekly, monthly, yearly)
- Manage entire series or delete forward from a specific date
- Events are linked with a unique Series ID

🏷️ **Smart Filtering**
- Filter events by tags in real-time
- Toggle minor events on/off to focus on major milestones
- Responsive search experience

💾 **Data Portability**
- Export your timeline as JSON for backup and sharing
- Import previously exported timelines
- All data stored securely in browser localStorage

🖥️ **Fullscreen Mode**
- View your timeline in immersive fullscreen
- Press ESC to exit
- Optimized responsive design

## Getting Started

1. **Open the application**:  Simply open `timeline_20260101_05.html` in your web browser
2. **Add your first event**: Fill out the form at the bottom with: 
   - Date and time
   - Event title
   - Description
   - Optional: tags, images, and more
3. **Click "Add Event"** and watch it appear on the timeline
4. **Select events** on the timeline to view full details

## Usage Guide

### Adding Events
- Fill in the date, title, and description
- Add comma-separated tags (e.g., `travel, career, family`)
- Include image URLs (one per line)
- Check "Mark as Minor Event" for less significant memories
- Click "Add Event" to save

### Recurring Events
- Check the "Recurring Event?" checkbox
- Select frequency:  Daily, Weekly, Monthly, or Yearly
- Set a "Repeat Until" date
- The app will generate individual events linked by a Series ID
- You can delete single instances or all future events in the series

### Managing Your Timeline
- **Edit**: Click "Edit" on any event to modify it
- **Delete**: Remove a single event with "Delete"
- **Delete Forward**: Remove an event and all future events in its series
- **Export**: Save your timeline as a JSON file
- **Import**: Load a previously exported timeline

### Filtering & Navigation
- Use the **tag filter** to search for specific types of events
- Toggle **Show Minor Events** to focus on major milestones
- Use the timeline zoom controls to explore different time periods
- Click **Fullscreen** for an immersive view

## Technologies Used

- **[Vis.js Timeline](https://visjs.org/)**: Interactive timeline visualization
- **[Google Fonts - Inter](https://fonts.google.com/specimen/Inter)**: Modern, clean typography
- **HTML5 + CSS3 + JavaScript**: Pure frontend, no backend required
- **Browser LocalStorage**: Client-side data persistence

## Browser Compatibility

Works best on modern browsers with ES6 support: 
- Chrome/Edge 60+
- Firefox 55+
- Safari 10+

## Data Storage

All your events are stored in your browser's **localStorage**. This means:
- ✅ Your data stays on your device (privacy-first)
- ✅ No account or login required
- ⚠️ Data persists only in that browser (clearing cache may delete data)
- 💾 **Always export backups** of your timeline

## Tips & Tricks

- Use **tags wisely** to organize your life (career, travel, family, health, education, etc.)
- Create **series of recurring events** for habits or annual celebrations
- Mark **minor events** to avoid cluttering your main timeline view
- **Export regularly** to keep secure backups of your memories
- Use **fullscreen mode** to get inspired by your achievements and journey

## Future Ideas

- Dark mode theme
- Multiple timelines
- Calendar view option
- Statistics and life insights
- Mobile app version

## License

Open source - feel free to use, modify, and share!

## Contributing

Found a bug or have a feature suggestion? Feel free to open an issue or submit a pull request!

---

**Made with ❤️ for documenting life's moments**
