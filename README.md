# **HostelConnect**

## **Overview**
HostelConnect is a mobile application built for Android, with **Jetpack Compose** and **Firebase**. The app streamlines the process of viewing hostel details and booking viewing appointments for students. It includes features such as **user authentication**, a list of hostels with detailed views, and a simple appointment request system.

---

## **Features**
- **User Authentication**: Secure login and signup for students.
- **Hostel Listings**: View a list of available hostels with key details.
- **Hostel Details**: Detailed information about each hostel, including facilities, location, and pricing.
- **Appointment Requests**: Submit a form to request an appointment with the hostel manager.

---

## **Technology Stack**
### **Languages**
- Kotlin

### **Frameworks & Libraries**
- **Jetpack Compose**: UI framework for building native Android UIs.
- **Jetpack Navigation**: For handling app navigation.
- **Firebase Authentication**: User authentication (optional).

---

## **Setup Instructions**
### **1. Clone the Repository**
```bash
git clone https://github.com/CindyMG/HostelConnect_App.git
cd hostelconnect
```

### **2. Open the Project in Android Studio**
- Ensure you have the latest version of **Android Studio** installed.
- Open the `HostelConnect` folder in Android Studio.

### **3. Configure Dependencies**
- Sync the project to download dependencies by clicking on **Sync Now** in the `build.gradle` files.

### **4. Database Initialization**
No additional setup is required for the Room database. The app initializes and creates the database on the first launch.

### **5. Run the Application**
- Connect an Android device or start an emulator.
- Click **Run** or use the shortcut `Shift + F10`.

---
## **App Flow**
1. **Login/Signup**: Users can log in or create an account.
2. **Hostel List**: Browse available hostels with basic details.
3. **Hostel Details**: View more information about a selected hostel.
4. **Request Appointment**: Fill a simple form to book a hostel visit.

---

## **Future Enhancements**
- Add Google Maps integration for hostel locations.
- Implement a notification system for appointment confirmations.
- Enable reviews and ratings for hostels.
- Add analytic tools for hostel managers.

---

## **Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Create a Pull Request.

---

## **License**
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---
