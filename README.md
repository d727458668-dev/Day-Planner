#  Day Planner with Alerts

A simple and interactive **Day Planner Web Application** built using **HTML, CSS, and JavaScript**.  
This application allows users to organize daily tasks, schedule reminders, categorize activities, and export task data to an Excel file.

The planner includes **task notifications, daily summaries, and local storage support**, making it useful for managing work, study, and personal activities efficiently.

---

#  Features

- 📅 Add tasks with **date and time**
- 🗂️ Categorize tasks (**Work, Personal, Study**)
- 🔔 **Browser notifications** for upcoming tasks
- ⏰ Alerts **5 minutes and 1 minute before** a task
- 📋 **Daily task summary notification**
- 🗑️ Delete tasks easily
- 💾 **Local storage support** (tasks remain after page refresh)
- 📤 **Export tasks to Excel file**
- 🎨 Modern **glassmorphism UI design**
- 📱 Responsive layout

---

#  Technologies Used

- **HTML5** – Structure of the web application  
- **CSS3** – Styling and animated background  
- **JavaScript (Vanilla JS)** – Application logic  
- **LocalStorage API** – Saving tasks locally  
- **Browser Notifications API** – Task reminders  
- **SheetJS (XLSX library)** – Exporting tasks to Excel  

---


All the code (HTML, CSS, and JavaScript) is contained in a single **HTML file** for simplicity.

---

# How It Works

1. The user enters a **task description**.
2. The user selects a **date and time**.
3. A **category** is chosen for the task.
4. When the task is added:
   - It is stored in **localStorage**.
   - It appears in the **task list**.
   - Notifications are scheduled automatically.
5. The system sends alerts:
   - **5 minutes before the task**
   - **1 minute before the task**
6. Every morning at **8:00 AM**, the planner shows a **daily summary notification** of all tasks scheduled for that day.

---

#  Notification System

The application uses the **Browser Notification API**.

Notifications include:
- Upcoming task reminders
- Task time and category
- Daily task summary

The browser will ask permission to enable notifications when the application starts.

---

#  Export to Excel

Users can export all tasks into an **Excel (.xlsx) file** using the **Export to Excel** button.

The exported file includes:

- Task name  
- Task date  
- Task time  
- Task category  

This feature uses the **SheetJS XLSX library**.

---

#  Local Storage

Tasks are saved using the **LocalStorage API**, which means:

- Tasks remain saved even after refreshing the page
- No database is required
- Data is stored locally in the browser

---



