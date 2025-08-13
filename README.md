# 📅 Productivity Calendar

A beautiful, feature-rich calendar application built with vanilla HTML, CSS, and JavaScript. Perfect for managing your daily tasks, events, and appointments with a modern, responsive interface.

![Productivity Calendar Screenshot](https://via.placeholder.com/800x400/667eea/ffffff?text=Productivity+Calendar+Screenshot)

## ✨ Features

### 🗓️ Multiple View Modes
- **Month View**: Traditional calendar grid layout
- **Week View**: Detailed weekly schedule with hourly time slots
- **Day View**: Focus on a single day's events and tasks

### 📝 Event Management
- Create, edit, and delete events with ease
- Rich event details including title, date, time, and description
- Color-coded categories for better organization
- Quick event creation by clicking on any date

### 🔔 Smart Reminders
- Configurable reminder notifications
- Options: 15 minutes, 30 minutes, 1 hour, or 1 day before
- Browser notifications for upcoming events

### 🎨 Beautiful Design
- Modern gradient-based UI design
- Responsive layout that works on all devices
- Smooth animations and hover effects
- 8 beautiful color categories for event organization

### 💾 Data Persistence
- Local storage saves all your events
- No server required - works completely offline
- Export calendar to ICS format for other applications

### ⌨️ Keyboard Shortcuts
- `Ctrl + N`: Add new event
- `Escape`: Close modal dialogs

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or servers required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/productivity-calendar.git
   cd productivity-calendar
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html  # macOS
   start index.html # Windows
   xdg-open index.html # Linux
   ```

   Or drag and drop `index.html` into your browser window.

## 📁 Project Structure

```
productivity-calendar/
├── index.html          # Main HTML structure
├── style.css           # Stylesheet with modern design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── screenshots/        # Project screenshots (optional)
```

## 🎯 Usage

### Adding Events
1. Click the **"+ Add Event"** button or click on any calendar date
2. Fill in the event details:
   - Event title (required)
   - Date (required)
   - Time (optional - leave blank for all-day events)
   - Description (optional)
   - Reminder setting
   - Color category
3. Click **"Save Event"**

### Editing Events
- Click on any existing event to edit its details
- Use the **"Delete"** button to remove events
- Changes are saved automatically to local storage

### Navigation
- Use **"Previous"** and **"Next"** buttons to navigate between months/weeks/days
- Switch between Month, Week, and Day views using the view buttons
- Today's date is automatically highlighted

### Exporting Calendar
- Click **"Export ICS"** to download your calendar
- Import the `.ics` file into Google Calendar, Outlook, or other calendar applications

## 🛠️ Customization

### Adding New Color Categories
Edit the color options in `index.html`:
```html
<div class="color-option" data-color="#your-color" style="background: #your-color;"></div>
```

### Modifying Reminder Options
Update the reminder select options in `index.html`:
```html
<option value="your-minutes">Your custom time</option>
```

### Styling Changes
Modify `style.css` to customize:
- Color schemes and gradients
- Font sizes and families
- Layout and spacing
- Animation effects

## 🌟 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome  | 60+     | ✅ Full |
| Firefox | 55+     | ✅ Full |
| Safari  | 11+     | ✅ Full |
| Edge    | 79+     | ✅ Full |

## 📱 Mobile Support

The calendar is fully responsive and optimized for mobile devices:
- Touch-friendly interface
- Optimized layouts for small screens
- Swipe-friendly navigation
- Mobile-specific styling

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup and modern features
- **CSS3**: Flexbox, Grid, gradients, and animations
- **JavaScript ES6+**: Modern JavaScript features
- **LocalStorage API**: Client-side data persistence

### Performance Features
- Lightweight vanilla JavaScript (no frameworks)
- Optimized rendering for large event datasets
- Efficient event delegation for click handling
- Minimal DOM manipulation for smooth performance

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Setup
1. Clone the repository
2. Make your changes
3. Test in multiple browsers
4. Ensure responsive design works
5. Submit your pull request

## 🐛 Known Issues

- Browser notifications require user permission
- ICS export format may vary between calendar applications
- LocalStorage has size limitations (typically 5-10MB)

## 📋 Roadmap

- [ ] Recurring events support
- [ ] Calendar sharing functionality
- [ ] Integration with Google Calendar API
- [ ] Dark mode theme
- [ ] Event search and filtering
- [ ] Drag-and-drop event rescheduling
- [ ] Multiple calendar support
- [ ] Print functionality

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🙏 Acknowledgments

- Inspired by modern calendar applications
- Icons and design patterns from contemporary UI/UX trends
- Color palette inspired by modern gradient designs

## 📞 Support

If you have any questions or need help:
- Create an issue on GitHub
- Check existing issues for solutions
- Review the documentation above

---

<div align="center">
  <strong>Made with ❤️ for productivity enthusiasts</strong>
  <br><br>
  ⭐ Star this repo if you found it helpful!
</div>
