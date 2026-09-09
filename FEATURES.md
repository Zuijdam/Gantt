# Gantt Chart - New Features

## Feature 1: Password Protection ✅

A login screen now protects access to your Gantt chart application.

### How it Works:
1. When you open the application, a login modal appears
2. Enter the password to access the Gantt chart
3. The password is remembered during your browser session

### Default Password:
```
password123
```

### Features:
- Clean, modern login interface with gradient background
- Enter key submits the password
- Error messages for incorrect passwords
- Session-based authentication (closes when browser closes)

### Changing the Password:
To set a different password, edit `index.html` and find this line:
```javascript
const CORRECT_PASSWORD = 'password123';
```
Change `'password123'` to your desired password.

---

## Feature 2: New Chart Button ✅

A new "New Chart" button in the toolbar allows you to start a fresh Gantt chart.

### How it Works:
1. Click the yellow **"New Chart"** button in the toolbar
2. A confirmation dialog appears asking to verify
3. Click "OK" to clear all data and start fresh
4. All saved data is removed (will ask if you haven't saved)

### Benefits:
- Quick reset without page refresh
- Clears localStorage data
- Asks for confirmation to prevent accidents

---

## Quick Start Guide

1. **Load the application**: Open `index.html` in your browser
2. **Login**: Enter password `password123`
3. **Create tasks**: Add and organize your tasks as usual
4. **Save your work**: Click the "Save" button
5. **Start fresh**: Click "New Chart" when ready for a new project

---

## Notes

- The password is stored in the browser session (not persistent across browser restarts)
- All Gantt functionality remains the same
- Data is still saved to localStorage when you click "Save"
- You can export charts in various formats (PNG, PDF, Excel, iCal)

---

## Support

For more information on the original Gantt features, visit:
https://github.com/Carleslc/Gantt
