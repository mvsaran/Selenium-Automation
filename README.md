# 🧪 Selenium Automation Framework 🚀

<div align="center">

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![WebDriver](https://img.shields.io/badge/WebDriver-4EAA25?style=for-the-badge&logo=selenium&logoColor=white)

**A comprehensive Selenium WebDriver automation suite demonstrating real-time web interaction scenarios**

[Features](#-features-covered) • [Installation](#-installation) • [Usage](#-usage) • [Contributing](#-contributing)

</div>

---

## 📖 Overview

This repository contains a **robust Selenium WebDriver automation suite** implemented in Java that demonstrates automation of various real-time web interaction scenarios. It is designed as a hands-on reference for mastering different Selenium features and advanced user actions.

Perfect for QA engineers, automation testers, and developers looking to enhance their Selenium skills! 💡

---

## ✨ Features Covered

### 🔗 **Broken Link Validation**
Scan and detect dead hyperlinks across web pages to ensure link integrity.

### ☑️ **Checkbox Handling**
Select/deselect multiple checkboxes with advanced selection patterns.

### 🖼️ **Iframe Handling**
Switch and interact seamlessly with iframe content embedded in pages.

### 🪟 **Window Handling**
Manage and switch between multiple browser windows or tabs effortlessly.

### ⚡ **JavaScript Executor**
Run JavaScript commands like scrolls, clicks, or data entry for complex interactions.

### ⌨️ **Keyboard Actions**
Automate typing, keyboard shortcuts, and special key handling (Enter, Tab, etc.).

### 🖱️ **Mouse Hover Actions**
Hover to reveal menus, tooltips, and hidden elements.

### 📸 **Screenshots**
Capture screenshots during test execution for debugging and reporting.

### 📅 **Date Picker Automation**
Select dates from calendar widgets with precision and ease.

### 📋 **Dropdown Handling**
Select options by index, value, or visible text from dropdown menus.

### 🚨 **Alert Handling**
Manage JavaScript alerts, confirmations, and prompts programmatically.

### 📤 **File Upload Automation**
Upload files using sendKeys or Robot class for native file dialogs.

### 👻 **Headless Testing**
Run tests in a headless browser mode for CI/CD pipelines and faster execution.

### 🎯 **Locator Strategies**
Master different locator techniques: ID, XPath, CSS Selectors, Class Name, and more.

---

## 🛠️ Installation

### Prerequisites
- ☕ Java JDK 8 or higher
- 📦 Maven or Gradle
- 🌐 ChromeDriver/GeckoDriver (or WebDriverManager)

### Setup Steps

```bash
# Clone the repository
git clone https://github.com/yourusername/selenium-automation.git

# Navigate to project directory
cd selenium-automation

# Install dependencies
mvn clean install
```

---

## 🚀 Usage

Run individual test scenarios or execute the complete test suite:

```bash
# Run all tests
mvn test

# Run specific test class
mvn test -Dtest=CheckboxHandlingTest

# Run in headless mode
mvn test -Dheadless=true
```

---

## 📁 Project Structure

```
selenium-automation/
├── src/
│   ├── main/java/          # Core framework code
│   └── test/java/          # Test scenarios
├── drivers/                # WebDriver executables
├── screenshots/            # Captured screenshots
├── pom.xml                 # Maven configuration
└── README.md              # This file
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests

---

## 👨‍💻 Author

**Saran Kumar**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

### ⭐ If you find this helpful, please give it a star!

**Happy Testing!** 🎉

</div>
