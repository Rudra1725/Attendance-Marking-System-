# 📜 AttendFlow – Smart Attendance Tracker

AttendFlow is a lightweight, responsive web-based attendance management system designed to help students track their subject-wise attendance and maintain the required 75% attendance criteria.

It provides real-time attendance calculations, smart bunk calculations, attendance recovery suggestions, and automatic data storage directly in the browser.

## Features

- **Subject Management:** Add and delete subjects dynamically.
- **Attendance Tracking:** Mark individual lectures as Present or Absent.
- **Real-Time Calculations:** Automatically calculates subject-wise and overall attendance percentages.
- **75% Attendance Monitoring:** Instantly identifies whether attendance is above or below the required threshold.
- **Smart Bunk Calculator:** Calculates how many upcoming lectures can be missed while maintaining 75% attendance.
- **Attendance Recovery:** Shows how many consecutive lectures must be attended to recover to 75%.
- **Undo Functionality:** Revert the last attendance action for any subject.
- **Automatic Data Storage:** Saves attendance records using browser LocalStorage.
- **Dashboard Overview:** Displays total lectures, attendance percentage, and course health.
- **Responsive Interface:** Works across desktop and mobile screens.
- **Reset Demo:** Restore the default sample subjects.

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| Tailwind CSS | Styling and responsive layout |
| JavaScript | Application logic and calculations |
| LocalStorage | Persistent browser-side data storage |
| Phosphor Icons | Interface icons |
| Google Fonts | Plus Jakarta Sans typography |

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/AttendFlow.git
```

### 2. Navigate to the Project Directory

```bash
cd AttendFlow
```

### 3. Run the Application

Open `index.html` in your preferred web browser.

No installation, backend server, or database setup is required.

## How It Works

1. Add your college subjects using the Add Subject option.
2. Select **Present** when you attend a lecture.
3. Select **Absent** when you miss a lecture.
4. Monitor your attendance percentage in real time.
5. Check the dashboard to understand your overall attendance status.
6. Use the smart attendance suggestions to plan upcoming lectures.

## Attendance Calculation

The application uses the following formula:

**Attendance Percentage**

```text
(Attended Lectures / Total Lectures) × 100
```

**Example:**

```text
Attended Lectures = 21
Total Lectures    = 24

Attendance = (21 / 24) × 100
           = 87.5%
```

The application uses 75% as its default attendance monitoring threshold.

## Data Storage

AttendFlow uses the browser's LocalStorage API to save attendance information.

- Data persists after refreshing the page.
- No account or login is required.
- Data remains specific to the browser and device.
- Clearing browser storage may permanently remove saved attendance records.

## Project Structure

```text
AttendFlow/
│
└── index.html
```

## Limitations

- No backend or cloud database integration.
- No account authentication.
- Attendance data does not synchronize across devices.
- Attendance records are stored locally in the browser.

## Future Improvements

- Export attendance reports as PDF or CSV.
- Attendance history with date-wise records.
- Cloud synchronization.
- Subject-wise attendance analytics.
- Import and export attendance data.

## License

This project is licensed under the MIT License.

---

**AttendFlow** – Track your attendance. Stay informed. Stay eligible.
