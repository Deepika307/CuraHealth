# 🏥 CuraHealth Automation Framework

A robust Selenium-based Test Automation Framework built using **Java, TestNG, and Maven** to automate end-to-end testing of the CuraHealth web application.

This project follows industry best practices like **Page Object Model (POM)**, reusable utilities, and structured reporting for scalable and maintainable test automation.

---

## 🚀 Features

* ✅ Page Object Model (POM) architecture
* ✅ TestNG-based test execution
* ✅ Extent Reports integration
* ✅ Screenshot capture on test failure
* ✅ Centralized configuration management
* ✅ Reusable utilities (DriverFactory, ConfigReader, etc.)
* ✅ Data-driven testing support
* ✅ Clean and modular project structure

---

## 🛠️ Tech Stack

| Technology     | Usage                |
| -------------- | -------------------- |
| Java           | Programming Language |
| Selenium       | Browser Automation   |
| TestNG         | Test Framework       |
| Maven          | Build Tool           |
| Extent Reports | Test Reporting       |

---

## 📁 Project Structure

```text
CuraHealth/
│── pom.xml                         # Maven dependencies
│── .project                        # Eclipse project file
│── .classpath                      # Eclipse classpath
│
├── .settings/                      # IDE settings
│
├── reports/                        # Test execution reports
│   └── ExtentReport_*.html
│
├── screenshots/                    # Failure screenshots
│
├── src/
│   ├── main/
│   │   ├── java/com/srm/curahealth/
│   │   │   ├── base/
│   │   │   │   └── BasePage.java
│   │   │   │
│   │   │   ├── constants/
│   │   │   │   └── FrameworkConstants.java
│   │   │   │
│   │   │   ├── listeners/
│   │   │   │   └── TestListener.java
│   │   │   │
│   │   │   ├── model/
│   │   │   │   └── AppointmentData.java
│   │   │   │
│   │   │   ├── pages/              # Page Object classes
│   │   │   │   ├── LoginPage.java
│   │   │   │   ├── HomePage.java
│   │   │   │   ├── AppointmentPage.java
│   │   │   │   ├── ConfirmationPage.java
│   │   │   │   ├── HistoryPage.java
│   │   │   │   ├── ProfilePage.java
│   │   │   │   └── SidebarPage.java
│   │   │   │
│   │   │   ├── utils/              # Utility classes
│   │   │   │   ├── ConfigReader.java
│   │   │   │   ├── DateUtil.java
│   │   │   │   ├── DriverFactory.java
│   │   │   │   ├── ExtentManager.java
│   │   │   │   └── ScreenshotUtil.java
│   │   │
│   │   └── resources/
│   │       └── config.properties   # Configurations
│   │
│   ├── test/
│   │   ├── java/com/srm/curahealth/
│   │   │   ├── base/
│   │   │   │   └── BaseTest.java
│   │   │   │
│   │   │   ├── tests/              # Test classes
│   │   │   │   ├── AuthenticationTests.java
│   │   │   │   ├── AppointmentBookingTests.java
│   │   │   │   ├── AppointmentHistoryTests.java
│   │   │   │   ├── FormValidationTests.java
│   │   │   │   ├── MultipleAppointmentsTests.java
│   │   │   │   └── TestDataProviders.java
│
└── target/                         # Compiled files (ignored in Git)
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/CuraHealth.git
cd CuraHealth
```



---

## ▶️ Running Tests

* Right-click `testng.xml`
* Run as → TestNG Suite

---

## 📊 Reports

After test execution:

* 📄 Extent Reports are generated in:

```
/reports/
```

👉 Open the `.html` file in any browser to view results.

---

## 📸 Screenshots

* Automatically captures when a test fails
* Stored in:

```
/screenshots/
```

---

## 🔑 Configuration

Modify settings in:

```
src/main/resources/config.properties
```

You can configure:

* Browser (Chrome, Edge, etc.)
* Base URL
* Timeouts

---

## 🧪 Test Scenarios Covered

* 🔐 Authentication (Login/Logout)
* 📅 Appointment Booking
* 📜 Appointment History
* ⚠️ Form Validation
* 🔁 Multiple Appointments Handling

---

## 🧠 Framework Design Highlights

* **POM Design Pattern** for maintainability
* **DriverFactory** for browser management
* **Listeners** for logging and reporting
* **Reusable utilities** for scalability
* **Separation of concerns** across layers

---

## 👩‍💻 Author

**Deepika Kantheti**










