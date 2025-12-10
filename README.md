📅 Classic Timetable — Pro (HTML/JS Version)
A modern, interactive, weekly timetable app built using pure HTML, CSS, and Vanilla JavaScript, featuring dark mode, drag-and-drop rows, rich notes, advanced search, export/import tools, and Excel support via SheetJS.

This project is perfect for students, productivity lovers, or anyone who wants a visual weekly schedule inside their browser—no backend required!

✨ Features
🕒 Customizable Timetable
    Editable cells
    Add/Delete rows
    Drag & drop rows to reorder
    Editable time slots (supports ranges like 9:00 AM – 10:00 AM)

🌗 Dark Mode
    Manual toggle
    Auto-dark mode based on custom start/end times
    Remembers preferences in localStorage

📝 Notes Popup
    Add detailed notes to any cell
    Notes indicator dot (yellow = empty, green = filled)
    Modal view with Save/Close buttons

🔍 Smart Search
    Find by time (e.g., “9 AM”)
    Search by keyword inside tasks
    Results shown in beautifully formatted modal

📤 Export Options
    Export to JSON
    Export to CSV
    Export to Excel (XLSX) using SheetJS
    All downloads done client-side — no server

📥 Import JSON
    Upload previously exported .json timetable
    Instantly rebuilds the grid
    Validates structure before applying

📊 Weekly Summary
    Show all filled tasks only
    Sorted by weekday & time
    Print-friendly view
    Popup modal with smooth blur background

🔒 Local Storage Sync
Timetable stays saved even after closing the browser.

🛠️ Technologies Used
UI & Logic -	HTML, CSS, Vanilla JS
Excel Export -	SheetJS (XLSX) CDN
State Persistence -	localStorage
Time Parsing -	Custom JavaScript parser
Modals & UI	- Pure CSS + JS

📁 Folder Structure (recommended)
project/
│── index.html
│── README.md
│── assets/
│     └── icons, screenshots (optional)


🚀 How to Use
    Clone or download the repo
    Open index.html in any browser
    Start clicking, typing, dragging… everything just works
    Export your timetable or save notes
    Close the browser — your data is preserved 😎
    

🧠 Future Improvements (Ideas)
    Drag-to-select multiple cells
    Color-coding tasks
    Cloud sync
    Mobile-friendly compact mode
    Google Calendar export

❤️ Motivation
Because planning your week shouldn’t feel like debugging someone else’s code.
This project keeps things simple, elegant, and actually usable.
