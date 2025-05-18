# 🩸 Blood Bank Management System (PHP + MySQL)

This is a web-based Blood Bank Management System developed using PHP and MySQL. It allows users to register, log in, and request blood. Admins can manage users, donations, and track blood availability via a dedicated admin dashboard.


## 📁 Project Structure

├── admin/ # Admin dashboard files
├── admin_dasboard/ # Additional admin dashboard files (possible typo, check for redundancy)
├── user_dashboard/ # User dashboard files
├── connection.php # Database connection configuration
├── footer.php # Common footer
├── header.php # Common header
├── index.php # Landing/home page
├── login.php # Login page
├── logout.php # Logout script
├── member_register.php # Member registration backend
├── register.php # User registration form




---

## 🚀 Features

- 📝 User registration and authentication
- 🔐 Secure login/logout with sessions
- 👥 Separate dashboards for Admin and Users
- 🩸 Blood request and donor management
- 📊 Admin analytics and control panel
- 🧱 Reusable components (header/footer)



## 🛠️ Technologies Used

- **Frontend:** HTML, CSS
- **Backend:** PHP
- **Database:** MySQL



$conn = mysqli_connect("localhost", "root", "", "blood_bank");


## 💾 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/prakriti33/blood-bank-management.git

