## 🤖 **FaceDetectApp**

### **Introduction**
FaceDetectApp is an Android application designed to detect and recognize faces using machine learning techniques. The app utilizes camera functionality to capture images and process them for face detection, providing real-time feedback and recognition results.

### **Features**
- **Real-Time Face Detection:** Detect faces in real-time using the device camera.
- **Face Recognition:** Identify and recognize faces from a pre-trained model.
- **Capture and Save Images:** Take photos and save detected faces for future reference.
- **Display Results:** Show detected faces with bounding boxes and recognition results.

### **Tech Stack**
- **Programming Language:** Java
- **Framework:** Android SDK
- **Architecture:** MVVM (Model-View-ViewModel)
- **UI Design:** XML
- **Libraries and APIs:**
  - **Google ML Kit:** For face detection and recognition.
  - **CameraX:** For camera functionality and image capture.
  - **Room:** For local database management to store images and detection data.
  - **LiveData:** For observing data changes and updating the UI.
  - **ViewModel:** For managing UI-related data in a lifecycle-conscious way.
- **Build Tool:** Gradle
