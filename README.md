# Aptitude Wizard

## 📌 Overview
Aptitude Wizard is a web-based application designed to help users practice and improve their aptitude skills. It provides a collection of aptitude tests with various categories, allowing users to enhance their problem-solving abilities effectively.

## 🚀 Features
- Multiple aptitude question categories
- User-friendly interface
- Real-time scoring system
- Track progress and performance
- Secure and scalable Django backend

## 🛠️ Installation
Follow these steps to set up and run Aptitude Wizard locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/chenchugokuljangam13/Aptitude_Wizard.git
cd Aptitude_Wizard
```

### 2️⃣ Set Up a Virtual Environment (Recommended)

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```


### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations

```bash
python manage.py migrate
```

### 5️⃣ Run the Development Server

```bash
python manage.py runserver
```
Now, open http://127.0.0.1:8000/ in your browser to access the application.

## 📂 Project Structure

```bash
Aptitude_Wizard/
│── ApptitudeWizard/
│── aptitude/         # Main Django app containing core functionality
│── templates/        # HTML templates for frontend
│── manage.py         # Django project management script
│── requirements.txt  # List of dependencies
│── .gitignore        # Files to be ignored by Git
│── db.sqlite3        # Local database (ignored in Git)
```


### 📌 Usage
- Navigate through the website to select different aptitude categories.
- Answer the questions and get immediate feedback.
- Track your performance over time.

### 🛠️ Technologies Used
- **Backend**: Python, Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (can be switched to PostgreSQL or MySQL)

