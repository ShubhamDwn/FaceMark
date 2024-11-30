# FaceMark
**FaceMark** is a face recognition-based attendance system that automates the process of marking attendance. By leveraging facial recognition technology, the system ensures accurate and efficient attendance tracking, eliminating the need for manual methods. It is ideal for educational institutions, workplaces, and events.

## Features
**Face Detection and Recognition:** Uses advanced algorithms to identify and verify faces.

**Automated Attendance:** Marks attendance instantly upon face recognition.

**User-Friendly Interface:** Simple and intuitive for both administrators and users.

**Scalable:** Supports multiple users and large datasets.

**Secure Data Storage:** Ensures attendance records are safely stored and easily retrievable.

## Requirements:
Ensure you have the following dependencies installed:

Python (>= 3.7)

OpenCV

NumPy

Pandas

Face Recognition Library (e.g., dlib or face_recognition)


### Install dependencies with:

**bash**

pip install -r requirements.txt

### How It Works
**Face Enrollment:** Capture and store images of participants for reference.

**Face Recognition:** Detect and verify faces in real time using the webcam.

**Attendance Marking:** Automatically update the attendance record upon successful recognition.

**Data Storage:** Attendance logs are saved in a database or CSV file for later access.

## Usage
Clone the repository:

**bash**

git clone https://github.com/ShubhamDwn/FaceMark.git

cd FaceMark

Enroll faces by running:

**bash**

python enroll_faces.py

Follow the prompts to register users.

#### Start the attendance system:

##### bash

python mark_attendance.py

View attendance records:

##### bash

python view_records.py


#### Example

**Input:** A live feed from a webcam or an uploaded image.

**Output:** The recognized face is logged as present, with the timestamp stored in the attendance records.


## Future Enhancements
Add support for multi-camera setups.

Introduce a mobile app for remote attendance tracking.

Implement cloud-based storage for seamless record management.

Enhance recognition accuracy under different lighting conditions.

## Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request. Ensure all contributions align with the project goals.


## Author
Developed by Shubham Dhavan and Team.

Feel free to reach out for queries, feedback, or collaborations!
