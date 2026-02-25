# Weather-App

A desktop weather application developed using **Java** and **JavaFX**.  
This project demonstrates a multi-screen graphical user interface built with FXML, styled using CSS, and controlled through Java controller classes. It also includes JSON data handling for managing weather information.

---

## 📌 Project Overview

Weather-App is a JavaFX-based desktop application that displays weather information in an interactive and user-friendly interface. The application includes a dashboard view, a five-day forecast view, and a map view.

The project follows a structured approach using:

- FXML files for UI layout
- Controller classes for logic handling
- CSS for styling
- JSON processing classes for weather data management

This project is suitable for students and beginners learning:

- JavaFX application development
- FXML and Controller integration
- Event-driven programming
- JSON data parsing in Java
- Desktop GUI application design

---

## 🚀 Features

- 🌤 Dashboard displaying current weather information
- 📅 Five-day weather forecast view
- 🗺 Map interface view
- 🎨 Custom CSS styling
- 🔄 Navigation between multiple screens
- 📦 JSON data handling for weather information
- 🖥 JavaFX desktop GUI application structure

---

## 📂 Project Structure

Weather-App/
│
├── Dashboard.fxml
├── dashboard_Style.css
├── DashboardController.java
├── fiv.fxml
├── Five_day.fxml
├── Five_dayController.java
├── FXMain.java
├── JASONBulkData.java
├── JSONDataCollection.java
├── map.fxml
├── MapController.java


### File Descriptions

- **FXMain.java** – Main class that launches the JavaFX application  
- **Dashboard.fxml** – Main dashboard UI layout  
- **DashboardController.java** – Controls dashboard functionality  
- **Five_day.fxml** – Five-day forecast UI layout  
- **Five_dayController.java** – Controls five-day forecast logic  
- **map.fxml** – Map interface layout  
- **MapController.java** – Controls map interactions  
- **dashboard_Style.css** – CSS styling for UI components  
- **JASONBulkData.java** – Handles bulk JSON weather data  
- **JSONDataCollection.java** – Parses and organizes JSON data  

---

## 🛠 Technologies Used

- Java (JDK 11 or later recommended)
- JavaFX
- FXML
- CSS
- JSON Processing

---

## ⚙️ Installation & Setup

### Option 1: Run Using an IDE (Recommended)

1. Install Java JDK (11 or later).
2. Download and configure JavaFX SDK.
3. Open the project in an IDE (IntelliJ IDEA, Eclipse, or NetBeans).
4. Add JavaFX libraries to the project.
5. Run `FXMain.java` as a Java application.

---

### Option 2: Run Using Command Line

Replace `/path/to/javafx-sdk/lib` with your JavaFX SDK lib directory.

Compile:
javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml *.java
Run:
java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml FXMain
---

## 🔧 Configuration

- Ensure all FXML files and CSS files are properly linked in the project.
- If connecting to a real weather API, add your API key securely (do not hard-code it).
- JSON files or API responses should match the structure expected by the JSON handling classes.

---

## 🔮 Future Improvements

- Integrate live weather API (e.g., OpenWeatherMap)
- Add location search functionality
- Improve UI design and animations
- Add error handling for network failures
- Implement offline data caching
- Package as a standalone executable application

---

## 🎯 Purpose of the Project

This project was developed for academic and learning purposes to understand:

- JavaFX application architecture
- GUI development with FXML
- Controller-based design pattern
- JSON data processing in Java
- Desktop application development workflow

---

## 📄 License

This project is open-source and free to use for educational purposes.
You may add an MIT License file if you wish to define usage rights.

---