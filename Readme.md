# Online Notes Sharing System (ONSS)

This project is a **PHP and MySQL-based application** for managing and sharing notes. Follow the instructions below to install, set up, and run the project.

---

## 🎥 Output Preview  
*yaaaha woh onssop.gif*  
![ONSS Output](onssop.gif)  

---

## 🚀 How to Install and Run the Project  

### **1. Prerequisites**  
Before starting, ensure the following:

- **XAMPP, WAMP, or LAMP** is installed on your system.  
- Basic knowledge of running a local server.  
- A web browser to access the application.  
- **git** installed (optional if cloning from a repository).  

---

### **2. Installation Steps**  

#### **Clone or Download the Project**  
- Clone the repository:  
  ```bash  
  git clone https://github.com/yashyyash/ONSS.git  
  ```  
- Or download the zip file and extract it.

---

### **3. Place the Project Folder in the Root Directory**  
- For **XAMPP**: Copy the `onss` folder into `C:\xampp\htdocs`.  
- For **WAMP**: Copy the `onss` folder into `C:\wamp\www`.  
- For **LAMP**: Copy the `onss` folder into `/var/www/html`.  

---

### **4. Set Up the Database**  
1. Open a browser and go to: [http://localhost/phpmyadmin](http://localhost/phpmyadmin).  
2. Create a new database named: `onssdb`.  
3. Import the SQL file:  
   - Navigate to the **SQL Files** folder in the project directory.  
   - Upload and import the `onssdb.sql` file into the `onssdb` database.

---

### **5. Run the Application**  
- Open a browser and navigate to: [http://localhost/onss](http://localhost/onss).

---

## 📝 User Credentials  

### **Employee/User Panel**  
- **Username**: `john12@gmail.com`  
- **Password**: `Test@123`

*Alternatively, you can register as a new user through the application.*

---

## 💡 Troubleshooting  

### **Common Issues**  

1. **Error 404**:  
   - Ensure the `onss` folder is in the correct directory (e.g., `C:\xampp\htdocs\onss`).  

2. **Database Connection Error**:  
   - Open the configuration file (e.g., `config.php` or `db.php` in the project folder).  
   - Verify the database credentials:  
     ```php  
     $servername = "localhost";  
     $username = "root";  
     $password = "";  
     $dbname = "onssdb";  
     ```  

3. **Blank Screen**:  
   - Check the PHP error logs in `xampp/php/logs`.

---

## 📖 Project Features  

- User-friendly panel for uploading and managing notes.  
- Secure login and registration functionality.  
- Easily customizable database and front-end.  

---

Feel free to contribute to this project by creating pull requests or reporting issues on GitHub.
