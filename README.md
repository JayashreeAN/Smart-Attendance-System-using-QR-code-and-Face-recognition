# Smart Attendance System using QR Code and Face Recognition

A smart and secure attendance system that combines **QR code scanning** and **face recognition** to automate the process of marking attendance. Built using Python and Flask, this system ensures accurate tracking while preventing proxy attendance.

## Highlights

- Dual-authentication: QR + Face
- Real-time face recognition using webcam
- Snapshots saved for verified attendance
- Web-based interface for easy use
- Logs attendance with time and user info

## How It Works

1. **Capture Faces** – Register users by capturing face images.
2. **Generate QR** – Admin creates QR code for a session.
3. **Scan QR & Recognize Face** – Users scan the QR and are verified using facial recognition.
4. **Mark Attendance** – Attendance is marked only when both QR and face match.

## Project Structure

- `main.py` – Core application logic  
- `templates/` – Webpages  
- `qrcodes/` – Generated QR images  
- `dataset/` – Stored face data  
- `recognized_faces/` – Snapshots of recognized users  
- `attendance_log.csv` – Attendance records  

## Note

This project is for educational and demonstration purposes. Make sure your webcam is working before you start.
