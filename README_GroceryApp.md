#GroceryApp

**GroceryApp** is an Android application that demonstrates proficiency in modern Android development practices including **API integration**, **UI design**, **Dependency Injection (Hilt)**, and **Unit Testing**.  

This project was developed as part of the **NIT3213 Android Application Development** assessment to showcase a complete app workflow — from login to data display and detail viewing — using clean architecture principles.

---

## 🚀 Overview

The app has three primary screens:

1. **Login Screen** – Users log in with their first name and student ID.  
2. **Dashboard Screen** – Displays a list of entities retrieved from the API using a RecyclerView.  
3. **Details Screen** – Shows detailed information about a selected entity.

The app interacts with the **vu-nit3213-api** for authenticating users and fetching data.

---

## ✨ Features Implemented

- 🔑 **User Login with API Authentication**  
- 📋 **Display Entities** using `RecyclerView` on the Dashboard  
- 🔍 **Detailed View** on a separate Details screen  
- 🧩 **Dependency Injection** with **Hilt**  
- ⚙️ **Asynchronous API Calls** with Kotlin **Coroutines**  
- 🧪 **Unit Tests** for ViewModels and core components  
- 🧭 **Clean Architecture** following MVVM pattern  
- 🧠 **Proper Git Usage** with meaningful commit history  

---

## 🧰 Tech Stack & Dependencies

| Library | Purpose |
|----------|----------|
| **AndroidX Core** (`androidx.core:core-ktx:1.13.1`) | Core Android extensions |
| **AppCompat** (`androidx.appcompat:appcompat:1.7.0`) | Backward compatibility |
| **Material Design** (`com.google.android.material:material:1.12.0`) | Modern UI components |
| **RecyclerView** (`androidx.recyclerview:recyclerview:1.3.2`) | Dynamic list display |
| **ConstraintLayout** (`androidx.constraintlayout:constraintlayout:2.1.4`) | Responsive layouts |
| **Lifecycle** (`androidx.lifecycle:lifecycle-runtime-ktx:2.8.6`) | MVVM lifecycle management |
| **Kotlin Coroutines** (`org.jetbrains.kotlinx:kotlinx-coroutines-android:1.9.0`) | Async operations |
| **Retrofit & Gson** (`com.squareup.retrofit2:retrofit:2.11.0`, `converter-gson:2.11.0`) | API and JSON handling |
| **OkHttp Interceptor** (`com.squareup.okhttp3:logging-interceptor:4.12.0`) | Network logging |
| **Hilt** (`com.google.dagger:hilt-android:2.51.1`) | Dependency Injection |
| **JUnit** (`junit:junit:4.13.2`) | Unit testing |
| **AndroidX Test & Espresso** (`androidx.test.ext:junit:1.1.5`, `androidx.test.espresso:espresso-core:3.5.1`) | UI testing |

---

## Setup Instructions

### Prerequisites

- **Android Studio Arctic Fox (or newer)**  
- **Android SDK 34**  
- **Stable Internet Connection** (for API access)

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sh1n-te/GroceryApp
   ```

2. **Open in Android Studio**
   - Go to **File → Open → Select project folder**
   - Allow Gradle to sync automatically

3. **Build the Project**
   - Click **Build → Make Project** or press `Ctrl + F9`

4. **Run the App**
   - Connect a device or emulator  
   - Click **Run → Run 'app'** or press `Shift + F10`

---

## Usage

1. Open the **MGoceryApp** app  
2. Enter:
   - **First Name** as username  
   - **Student ID (without ‘s’)** as password  
3. Tap **Login**  
4. View the list of entities on the **Dashboard**  
5. Tap an item to open the **Details Screen**

---

## Notes

- Ensure your device or emulator has **internet access** to interact with the API.  
- The app uses **Hilt** for dependency injection — perform a **Clean Build** if `@Inject` components fail to initialize.  
- Unit tests are included for key ViewModels and API logic.  

---

## Testing

To run unit tests:

```bash
./gradlew test
```

For instrumented (UI) tests:

```bash
./gradlew connectedAndroidTest
```


---

## Repository

All source files and resources are hosted on GitHub:  
👉 https://github.com/Sh1n-te/GroceryApp


---

## 👨‍💻 Author

**Sanskriti Thapa**  
Bachelor of Information Technology / NIT3213 Android Application Development  
Victoria University

---
