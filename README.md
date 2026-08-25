# 🏢 HR Assistant - Smart Attendance Analyzer

> A modern, client-side web application for analyzing, organizing, and visualizing employee fingerprint attendance records from raw biometric / Hikvision Excel exports.

---

## ✨ Features

- 📊 **Smart Raw Data Parsing**: Automatically parses raw check-in / check-out biometric attendance sheets (`.xls`, `.xlsx`, `.csv`).
- 👥 **Department & Employee Organization**: Automatically groups employees by department with instant search and filtering.
- ⏱️ **Work Hours & Overtime Calculation**: Accurately computes daily work duration, missing punch-ins/outs, and attendance summaries.
- 🌓 **Dark / Light Theme**: Beautiful modern glassmorphism UI with seamless dark mode support.
- 📥 **Clean Excel Export**: Export structured, cleaned-up attendance reports back into formatted Excel sheets.
- 🔒 **100% Privacy First**: All data processing is performed completely client-side inside the browser — no employee data is ever sent to external servers.

---

## 🛠️ Tech Stack

- **Frontend**: [Vue 3](https://vuejs.org/) (Reactivity & state management)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + Custom Glassmorphism UI
- **Excel Parser**: [SheetJS (xlsx)](https://sheetjs.com/)
- **Icons**: [Phosphor Icons](https://phosphoricons.com/)

---

## 🚀 Getting Started

Since the application is purely client-side with CDN dependencies, no build steps are required:

1. Clone or download the repository:
   ```bash
   git clone https://github.com/<YOUR_USERNAME>/hr-assistant.git
   cd hr-assistant
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari), or serve it using Live Server:
   ```bash
   # Optional: Using npx serve or Python
   npx serve .
   # or
   python -m http.server 8000
   ```

---

## 📋 Usage Guide

1. Drag and drop your attendance file (`.xls`, `.xlsx`, or `.csv`) onto the upload zone.
2. Choose a department from the dashboard to explore the team.
3. Select any employee to review their full attendance history, check-in/out timestamps, and total working hours.
4. Click **Export Report** to download the structured data.

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
