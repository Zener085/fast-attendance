# Fast Attendance System
Fast Attendance is a project developed by Team Алға Қазақстан from Innopolis University. The goal of the project is to
streamline the process of marking attendance at various university events, such as club meetings or exams.
The system utilizes facial recognition technology to identify individuals from a group photo, making attendance tracking
faster and more accurate.

---

## Features ##
- **User-Friendly Web Application:** The project includes a user-friendly web application developed using the Streamlit
                                     library. Users can register with their Innopolis University email, and the
                                     application allows for easy uploading of group photos for attendance tracking.
- **Face Detection and Recognition:** The system employs advanced face detection and recognition techniques.
                                      It initially uses the MTCNN (Multi-task Cascaded Convolutional Networks) for face
                                      detection and later applies a Siamese network for face recognition.
                                      These technologies contribute to accurate and efficient identification of
                                      individuals.
- **Training and Model Improvement:** The team worked on improving the initial face detection and recognition models.
                                      They experimented with different approaches, such as switching from the
                                      Haarcascade classifier to MTCNN for face detection and implementing a Siamese
                                      network for face recognition. The final models achieved impressive accuracy,
                                      making the system reliable for real-world applications.
- **Web Application Development:** The web application features multiple pages, including a homepage, a registration
                                   page for new users, and a page for scanning the room for attendance. Users can easily
                                   navigate through these pages to perform various tasks related to attendance tracking.

## Getting Started ##
As a student at Innopolis University, you can easily register on the [site](https://fastattendance.streamlit.app/) and
upload a photo to store your face in the system. You must do that before marking attendance anywhere. For main
instructors or club leaders who need to mark attendance, a simple group photo of all participants is all that's
required. Subsequently, you can obtain a CSV file containing the email addresses of all registered students.

## How to Use ##
To use the Fast Attendance system, follow these steps:
1. **Clone the Repository:**
   ```
   git clone https://github.com/Zener085/fast-attendance.git
   ```
2. **Install Dependencies:**
   ```
   pip install -r requirements.txt
   ```
3. **Run the Application:**
   ```
   streamlit run application.py
   ```
4. **Register New Users:**
   - Access the registration page to register new users by providing their Innopolis University email and scanning their
     faces.
5. **Scan the Room for Attendance:**
   - Use the scan photo page to capture a group photo and automatically identify individuals present. The system
     generates a CSV file with email addresses for attendance records.
6. **Download Attendance Records:**
   - After scanning, download the attendance records in CSV format for further processing.

## Contributors ##
- [Danil Kuchukov](https://github.com/xFonzie) (Web Developer, Researcher)
- [Artyom Makarov](https://github.com/Smulemun) (Face Recognition and Detection ML Developer)
- [Timofey Didenko](https://github.com/Zener085) (Face Detection ML Developer, Main Writer)

## References ##
- [OpenCV Cascade Classifier](https://docs.opencv.org/4.x/da/d53/tutorial_py_houghcircles.html)
- [MTCNN (Multi-task Cascaded Convolutional Networks)](https://arxiv.org/abs/1604.02878)
- [Siamese Network](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)
- [Streamlit Library](https://www.streamlit.io/)

## Final Thoughts ##
The Fast Attendance system aims to enhance the speed and accuracy of attendance tracking in educational institutions.
With its robust face detection and recognition capabilities, the project has the potential to revolutionize the way
organizations and clubs manage attendance records. Feel free to explore the project repository and contribute to its
ongoing development!