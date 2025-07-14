🩺 Medicine Reminder App
A lightweight Java desktop application to help users manage their daily medicine intake. Users can schedule medicine names along with the time (HH:mm format), and the app will alert them with a sound and popup notification at the specified time.

🚀 Features
Add medicine name and time.

Real-time reminder checks every minute.

Popup alert and audio notification when it’s time to take medicine.

Simple and clean GUI built using Java Swing.

Table to view all scheduled reminders.

💻 Technologies Used
Java (JDK 8 or later)

Java Swing (GUI)

Timer & TimerTask (for background reminder checking)

Java Sound API (javax.sound.sampled) for audio notifications

🛠 How to Use
Clone or download the repository.

Place a valid notification.wav file in the same folder.

Compile and run the MedicineReminderApp.java file.

bash
Copy
Edit
javac MedicineReminderApp.java
java MedicineReminderApp
Enter the medicine name and time in HH:mm format (e.g., 14:30).

The app will check every minute and notify you when it’s time.

📁 Folder Structure
Copy
Edit
medicine-reminder-app/
├── MedicineReminderApp.java
├── notification.wav
└── README.md
📌 Ideal For
Personal daily medication tracking

Elderly or patient care management

Java GUI learning and student projects

📈 Future Enhancements
Data storage using database or file

Recurring reminders

Calendar-based UI

Android/mobile version
