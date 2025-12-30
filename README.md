# 🎓 Student Management System (SMS) | Django CRUD Application

The **Student Management System (SMS)** is a full-stack, placement-ready web application built with **Python (Django)** to manage student records efficiently.  
It supports complete **CRUD (Create, Read, Update, Delete)** operations with a clean and responsive **UI using Bootstrap 5 and Bootswatch**, and stores data in **SQLite3**.  

This project demonstrates strong fundamentals in **backend development, frontend integration, database management, and MVT architecture**, making it ideal for **academic evaluation and placement interviews**.

---

## 🚀 Features

- ➕ Add new student records with validation  
- 📋 View all students in a responsive table  
- 👁️ View detailed student information using modal popups  
- ✏️ Edit/update student details  
- 🗑️ Delete student records with confirmation modal  
- 🎨 Responsive and modern UI using Bootstrap & Bootswatch  
- 🔐 CSRF protection for secure forms  
- 🗄️ SQLite3 database integration  

---

## 🛠️ Technology Stack

**Backend:** Python 3, Django  
**Frontend:** HTML5, CSS3, Bootstrap 5, Bootswatch, Font Awesome  
**Database:** SQLite3  

---

## 📁 Project Architecture

![Project Architecture](https://raw.githubusercontent.com/Zinb-NMK/Student-Managment-System-SMS-/main/arcstr.png)

---

## 🧩 Module Explanation

### Templates
- **base.html:** Common layout, navbar, footer, Bootstrap & Font Awesome integration  
- **index.html:** Displays all student records with view, edit, delete actions  
- **add.html:** Form for adding new students with success alerts  
- **edit.html:** Form for updating existing student details

### Forms (`forms.py`)
- Implemented with **Django ModelForm**  
- Fields: Student Number, First Name, Last Name, Email, Field of Study, GPA  
- Uses Bootstrap widgets for styling and validation  

### Models (`models.py`)
- **Student model** stores all student information  
- Fields match the ModelForm for consistent CRUD operations  

### Views (`views.py`)
- Handles **business logic** for Create, Read, Update, Delete  
- Renders templates and passes context data  
- Uses **POST requests** and CSRF protection for secure data handling  

### URLs (`urls.py`)
- Maps frontend URLs to corresponding views  
- Routes include: `index`, `add`, `edit/<id>`, `delete/<id>`  

---

## 🔄 CRUD Workflow

1. **Create:** User submits form → validated by ModelForm → saved to database  
2. **Read:** Fetch all records from database → display in table → detailed view via modal  
3. **Update:** Existing record loaded in form → user edits → updates saved to database  
4. **Delete:** Confirmation modal → POST request → record removed from database  

---

## ▶️ Installation & Setup

1. Clone the repository:
git clone https://github.com/your-username/Student-Management-System.git

2. Navigate to the project folder:
      cd Student-Management-System.

3. Create a virtual environment (optional):
      python -m venv venv


4. Activate the virtual environment:  
**Windows:**
      venv\Scripts\activate
**Linux / Mac:**
      source venv/bin/activate

6. Apply migrations:
      python manage.py makemigrations
      python manage.py migrate

7. Run the development server:
      python manage.py runserver

8. Open in your browser:
      http://127.0.0.1:8000/

## ▶️ Outputs

---

![Dashboard](https://github.com/Zinb-NMK/Student-Managment-System-SMS-/blob/main/Dashboard.png)
![Adding a Student](https://github.com/Zinb-NMK/Student-Managment-System-SMS-/blob/main/Add%20Student.png)
![Updating a Student](https://github.com/Zinb-NMK/Student-Managment-System-SMS-/blob/main/Update%20Student.png)
![Student Information](https://github.com/Zinb-NMK/Student-Managment-System-SMS-/blob/main/Info%20Pic.png)


---

## 👨‍💻 Author
**Nagaram Manoj Kumar**  
B.Tech – Computer Science (AI & ML)  
Aspiring Full-Stack & AI/ML Developer  

⭐ Educational & placement-ready project demonstrating Django CRUD, frontend integration, and database management














