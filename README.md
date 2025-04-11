# 🧠 Online Course Exam Platform (Django)

This project is part of the [IBM Full Stack Software Developer Professional Certificate](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer) on Coursera.

The Online Course Exam Platform is a Django-based web application that allows users to register, enroll in courses, and complete exams with automatic scoring. It features a full admin interface, user authentication, dynamic question rendering, and result evaluation with visual feedback.

---

## 📦 Project Structure

The application consists of the following key components:

- **Course & Lesson Management**: Courses with multiple lessons managed via Django Admin.
- **Question & Choice Models**: Dynamically rendered questions and multiple-choice answers.
- **Submission & Evaluation Logic**: User submissions are automatically scored server-side.
- **Exam Result View**: Clearly visualized results with color-coded answers and score.
- **Admin Interface**: Manage users, courses, enrollments, questions, and answers.
- **Authentication System**: Login and registration logic using Django’s built-in tools.

---

## 🚀 Features

- ✅ Enroll in online courses
- ✅ Take exams with dynamically generated questions and choices
- ✅ Submit answers and receive instant results
- ✅ Pass/fail feedback with score calculation
- ✅ Color-coded answer review (correct, missed, wrong)
- ✅ Admin tools to manage all content
- ✅ Responsive Bootstrap layout

---

## 🛠️ Technologies Used

- **Python 3.11**
- **Django 4.2.3**
- **SQLite** for local development database
- **Bootstrap 4** for styling and layout
- **HTML & Django Templating**
- **Django Admin** for data management

---

## 📂 Installation & Local Development

```bash
git clone https://github.com/<your-username>/tfjzl-final-cloud-app-with-database.git
cd tfjzl-final-cloud-app-with-database

# Create and activate virtual environment
python3 -m venv djangoenv
source djangoenv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser for admin access
python manage.py createsuperuser

# Start development server
python manage.py runserver
```

---

## 🔐 Admin Access

Visit: `http://127.0.0.1:8000/admin`  
Login with the credentials from your `createsuperuser` step.

Use the admin panel to:

- Add Instructors, Courses, Lessons
- Create Questions and multiple Choices
- Enroll users manually for testing
