

# Travel Guide App

A Python Tkinter-based travel assistant that brings together weather updates, maps, currency conversion, translation, world clocks, itinerary planning, and SOS alerts. Built as my first-semester project to explore real-world API integration and desktop app development.


---

## Table of Contents

* [About the Project](#about-the-project)
* [Features](#features)
* [Tech Stack & APIs](#tech-stack--apis)
* [Screenshots](#screenshots)
* [Getting Started](#getting-started)
* [Development Insights](#development-insights)
* [Future Enhancements](#future-enhancements)

---
## Screen Shots of the UI(TKINTER)
![447495135-520198ae-f109-4c43-91db-8be81ca4e6f5](https://github.com/user-attachments/assets/b701a8e4-820a-4644-b341-effb154b7c26)
![447495446-e0865881-9c1d-496a-886b-8614ad648630](https://github.com/user-attachments/assets/75af075c-ab45-49ae-a11d-f65311dd913d)
![447498333-e703c92a-f609-41bf-b309-3888d4af1483](https://github.com/user-attachments/assets/cf0941c7-ecf8-47e3-9e9d-effec6ec3f57)
![447498549-ba6f452c-b669-46fa-8705-5d31cb714583](https://github.com/user-attachments/assets/49c8c9be-604c-4e3a-82a3-3a4dc4f4abb4)
![447498701-3e245e29-8073-4cf3-b6b6-7f7e3bf18de5](https://github.com/user-attachments/assets/89c1d973-a8b8-4f50-8308-f530c68e6d20)
![447498870-087bf8bb-781f-4b22-9489-24dc2f477484](https://github.com/user-attachments/assets/9727e8b9-0301-4fef-84dd-be10391ae9cd)
![447499133-056bd200-d038-45e5-85f6-1461e4dedd7a](https://github.com/user-attachments/assets/486efdc7-3ace-47d1-a650-e9d1481e05bb)
![447499272-98e07e7b-d00a-4a8b-b5aa-870e4fa401b1](https://github.com/user-attachments/assets/5ff31055-8a03-4483-9c9b-6c9fe521bff8)
![447499773-b7093ed6-5283-4364-997f-9c8c3ec4b998](https://github.com/user-attachments/assets/d5022bff-3f5b-4ae4-9eff-e5eaad469af4)
![447499907-0d94bf4f-c321-4e3b-b86b-4cf2806cc4ed](https://github.com/user-attachments/assets/baf8ed44-4c50-4984-8ac4-b55c44ecf9b3)

---

## About the Project

This app was built in my first semester as a way to learn Python and apply what I was learning to a real-world project. It combines several travel-related features into one easy-to-use desktop application.

---

## Features

* User login and account creation
* Live weather updates using OpenWeatherMap API
* Interactive map with search
* Currency conversion with live exchange rates
* Language translation
* World clock with timezone support
* Itinerary planner with Excel export
* Emergency SOS popup for quick access
* Welcome screen with multilingual greetings

---

## Tech Stack & APIs

**Language & GUI:** Python, Tkinter
**APIs and Libraries Used:**

* OpenWeatherMap API (weather)
* ExchangeRate-API (currency)
* Googletrans (translation)
* tkintermapview (maps)
* pytz (timezones)
* Additional libraries: `requests`, `pandas`, `openpyxl`, `wikipedia`

---



## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/travel-guide-app.git
cd travel-guide-app
```

### 2. Install Dependencies

Install using the requirements file:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install wikipedia requests googletrans==4.0.0-rc1 pytz openpyxl pandas tkintermapview
```

### 3. Run the Application

```bash
python main.py
```

### 4. Default Login

Username: `admin`
Password: `admin123`
Or create a new account from within the app.

---

## Development Insights

This project helped me understand how to:

* Work with public APIs using Python
* Build desktop interfaces with Tkinter
* Organize code into modules
* Handle API errors and user inputs
* Design user-friendly and responsive layouts

---

## Future Enhancements

* Add hotel and flight search features
* Include itinerary reminders and alerts
* Introduce dark mode and theme options
* Consider building a mobile version with Kivy or PyQt

---



Built with ❤️ during my first semester as a hands-on learning experience.

Feel free to fork, contribute, or use this as a learning base.
