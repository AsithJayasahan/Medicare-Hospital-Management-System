# 🏥 Medicare Hospital Management System

A comprehensive **Hospital Management System (HMS)** built with **Laravel** and **MySQL**. This project streamlines the management of hospital operations, including patient registration, doctor assignment, appointments, treatments, billing, departments, and staff information—all with full **CRUD functionality**.

---

## 📽️ Project Demo Video


https://github.com/user-attachments/assets/4dc987b1-03ae-4105-b579-95a1dd5f7cac



---

## 🛠️ Tech Stack

- **Backend**: [Laravel 10+](https://laravel.com/)
- **Database**: MySQL
- **Frontend**: Blade (Laravel templating engine), Bootstrap
- **Authentication**: Laravel Breeze / Jetstream (or custom login/register)
- **IDE**: VS Code / PHPStorm

---

## 🔧 Features

- ✅ **Authentication**: Login/Logout/Register system
- 👨‍⚕️ **Doctors**: Add, edit, view, delete doctor profiles
- 🧑‍💼 **Staff**: Manage hospital staff information
- 🧾 **Patients**: Patient CRUD operations with medical history
- 📅 **Appointments**: Schedule, update, and delete appointments
- 💊 **Treatments**: Assign treatments to patients
- 💰 **Billing**: Generate and manage bills for patients
- 🏥 **Departments**: Organize hospital into departments
- 📊 **Dashboard**: Admin dashboard for summary reports

---

## 📁 Folder Structure

```
medicare-hms/
│
├── app/
│   ├── Http/Controllers/
│   ├── Models/
│
├── database/
│   ├── migrations/
│   ├── seeders/
│
├── resources/
│   └── views/
│       ├── patients/
│       ├── doctors/
│       ├── staff/
│       └── appointments/
│
├── public/
│   └── assets/
├── routes/
│   └── web.php
└── README.md
```

---

## ⚙️ Installation Instructions

### 📦 Clone the Repository

```bash
git clone https://github.com/yourusername/medicare-hospital-management-system.git
cd medicare-hospital-management-system
```

### 🧪 Install Dependencies

```bash
composer install
npm install && npm run dev
```

### ⚙️ Set Up Environment

```bash
cp .env.example .env
php artisan key:generate
```

Configure `.env` file for your **MySQL database**:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=medicare_hms
DB_USERNAME=root
DB_PASSWORD=your_password
```

### 🧬 Run Migrations & Seeders

```bash
php artisan migrate --seed
```

### ▶️ Serve the App

```bash
php artisan serve
```

Visit: `http://127.0.0.1:8000`

---

## 🔐 Admin Credentials (Optional)

```text
Email: admin@medicare.com
Password: 12345678
```

> Or create a new account from the Register page

---

## ✅ Status

This project is **complete** and functional for small to mid-size hospitals or clinics. Ready to be extended with:

- PDF report generation
- Role-based access control
- Email notifications
- API integration

---

## 👨‍💻 Author

**Your Name**  
🎓 Undergraduate Software Engineering Student  
📫 your.email@example.com  
🔗 [GitHub](https://github.com/yourusername)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

