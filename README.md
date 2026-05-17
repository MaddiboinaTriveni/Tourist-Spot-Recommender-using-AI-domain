# Tourist Spot Recommender Using AI

An AI-powered Flask web application that provides personalized tourist destination recommendations across India based on user preferences, categories, and locations.

## Live Demo

https://tourist-spot-recommender.onrender.com

---

## Features

* User Authentication System

  * Register
  * Login
  * Logout

* Personalized Tourist Spot Recommendations

* Filter Recommendations By:

  * Category
  * Location
  * Minimum Rating
  * Number of Recommendations

* Machine Learning Based Recommendation System

* Responsive User Interface

---

## Technologies Used

### Frontend

* HTML
* CSS
* Bootstrap

### Backend

* Flask
* Flask-Login
* Flask-SQLAlchemy
* Flask-WTF

### Machine Learning

* Scikit-learn
* Pandas
* NumPy
* Joblib

### Database

* SQLite

---

## Project Structure

```bash
Tourist-Spot-Recommender-using-AI-domain/
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── base.html
│   └── landing.html
│
├── models/
│   ├── random_forest_model.joblib
│   ├── label_encoders.joblib
│   ├── processed_data.csv
│   └── feature_importance.csv
│
├── app.py
├── recommender.py
├── extensions.py
├── models.py
├── requirements.txt
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/MaddiboinaTriveni/Tourist-Spot-Recommender-using-AI-domain.git
```

### Navigate to Project Folder

```bash
cd Tourist-Spot-Recommender-using-AI-domain
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

---

## Deployment

The project is deployed on Render.

Live Website:
https://tourist-spot-recommender.onrender.com

---

## Future Enhancements

* Add Tourist Spot Images
* Google Maps Integration
* Advanced Recommendation Algorithms
* Dark Mode Support
* User Reviews and Ratings
* Mobile Application Version

---

## Author

### Maddiboina Triveni

B.Tech Computer Science Engineering Student

GitHub:
https://github.com/MaddiboinaTriveni

