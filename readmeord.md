

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
* [License](#license)

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

## Screenshots

*(Add screenshots of your app UI here. For example: main menu, weather screen, map viewer, etc.)*

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

## License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you'd like me to generate this as a downloadable `README.md` file.
