# 🏋️ Fitness Tracking App

A simple **Fitness Tracking App** built with **Kotlin, MVVM architecture, Room Database, and RecyclerView**.  
The app allows users to log their daily fitness activities, calories burned, and workouts. Data is stored locally using Room DB and displayed in a clean dashboard with weekly progress charts (MPAndroidChart).  

---

## 🚀 Features
- 📌 Add, update, and delete fitness activities  
- 📊 Dashboard with bar chart for weekly progress  
- 🗂 Data persistence with **Room Database**  
- 🔄 MVVM Architecture with ViewModel + LiveData  
- 🎨 Clean and minimal UI using **ViewBinding**  

---

## 🛠 Tech Stack
- **Kotlin** – Main language  
- **Room Database** – Local data persistence  
- **MVVM Architecture** – For clean separation of concerns  
- **RecyclerView + Adapter** – For activity lists  
- **MPAndroidChart** – For fitness progress visualization  
- **ViewBinding** – For efficient UI handling  

---

## 📸 Screenshots
(Add your screenshots here after running the app)  
Example:
- Home Screen  
- Add Activity Screen  
- Dashboard (Charts)  
<img width="1080" height="2280" alt="Screenshot_1756124092" src="https://github.com/user-attachments/assets/b439190d-861e-4aa1-8168-7298299f5332" />
<img width="1080" height="2280" alt="Screenshot_1756124088" src="https://github.com/user-attachments/assets/9341b03e-8264-4dc7-83d8-b36b1ee0e77b" />
<img width="1080" height="2280" alt="Screenshot_1756124097" src="https://github.com/user-attachments/assets/e09fecf5-6fb2-46ed-91f3-8351050c6410" />

---
## 📂 Project Structure

FitnessTrackingApp/
│── app/
│ ├── adapter/ # RecyclerView Adapters
│ ├── dao/ # Room DAO
│ ├── db/ # Room Database
│ ├── entity/ # Data Models (Entities)
│ ├── fragment/ # UI Fragments (Home, Add, Dashboard)
│ ├── repository/ # Repository layer
│ ├── viewModel/ # ViewModels
│ ├── MainActivity.kt # Navigation host
│ ├── res/layout/ # XML UI layouts
│ └── AndroidManifest.xml

---

## ⚙️ Installation & Setup
1. Clone the repository:
bash git clone https://github.com/your-username/FitnessTrackingApp.git
`

2. Open the project in **Android Studio**
3. Sync Gradle to install dependencies
4. Run the app on an emulator or physical device

---

## 📌 Future Improvements

* 🔔 Add reminders/notifications for daily workouts
* 👤 User profiles and authentication
* 📱 Dark mode support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repo
2. Create a new branch (`feature-new`)
3. Commit changes and push
4. Open a pull request

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use and modify.

---

### 👩‍💻 Author

Developed by **Maliha Khokhar** ✨
