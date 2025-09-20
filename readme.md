# 📘 SIH 2025 Project – AutoEncoders

A web-based system built with **HTML, CSS, JavaScript and Python (Flask)** to manage student, mentor and admin interactions.  
The platform supports login authentication, attendance tracking, assignment uploads and data management.

---

## 🚀 FEATURES

- 🔑 **Login System** (Students, Mentors, Admins)  
- 📂 **Assignment Uploads and Management**
- 📊 **Student Data Handling** via CSV/Excel  
- 🧑‍🏫 **Mentor Dashboard**  
- 👨‍💻 **Admin Dashboard** for oversight  
- ⚡ Backend powered by **Flask** (Python)  

---

## 📂 Project Structure

SIH-2025-PROJECT--AUTOENCODERS--MAIN/
│── admin/ # Admin panel (HTML, CSS, JS)
│── assignments/ # Assignment Excel files
│── login/ # Login pages (HTML, CSS, JS)
│── mentor/ # Mentor dashboard
│── student/ # Student dashboard (not expanded in screenshot)
│── uploads/ # Uploaded files
│── venv/ # Virtual environment
│── app.py # Flask backend entry point
│── requirements.txt # Python dependencies
│── student_dt.csv # Student dataset
│── .gitignore # Git ignore rules
│── README.md # Project info


---

</details>

---

## ⚙️ Installation & Setup

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/sih-2025-project.git
cd sih-2025-project

# 2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run the Flask app
python app.py


📌 Open your browser and go to:
👉 http://localhost:8000/login/index.html


▶️ Usage

👨‍🎓 Student → Login & upload assignments
🧑‍🏫 Mentor → View & evaluate student submissions
👨‍💻 Admin → Manage assignments, mentors, and student data
