

---

# 🏖️ Tour-Travel-DBMS

<div align="center">  
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white">  
</div>  

<div align="center">  
  <h3>🌍 Database Management System for Travel & Tourism</h3>  
  <p>A complete booking platform for hotels, dining, transport & vacation packages</p>  
  <p><em>🎓 DBMS Project</em></p>  
</div>  

---

## ✨ Overview

**Tour-Travel-DBMS** is a database-driven travel and tourism management system. It allows customers to book hotels, restaurants, transportation, and tour packages online, while administrators can manage bookings, payments, and analytics.

---

## 🚀 Features

### 👤 User Management

* Secure registration & login
* Role-based access (Customer/Admin)
* Booking history & profile management

### 🏨 Hotel & Dining

* Hotel listings with amenities
* Room booking & availability tracking
* Restaurant management & table reservations

### 🚗 Transportation

* Multi-modal booking (flights, trains, buses, taxis)
* Route management & real-time seat availability

### 🌴 Vacation Packages

* Pre-designed & customizable packages
* Seasonal offers & group booking support

### 💳 Payments

* Secure payment gateway integration
* Billing, invoicing, refunds & loyalty rewards

---

## 🗄️ Database Schema

The database consists of **20+ normalized tables**, covering:

* **Users & Admins**
* **Hotels, Rooms & Amenities**
* **Bookings & Payments**
* **Transportation & Routes**
* **Dining & Reservations**
* **Tour Packages & Itineraries**

📌 Relationships include one-to-many (Hotels → Rooms), many-to-many (Users ↔ Packages), and foreign keys for integrity.

---

## 🛠️ Tech Stack

**Backend:** PHP, MySQL, Apache (XAMPP/WAMP)
**Database Tools:** phpMyAdmin, MySQL Workbench
**Other Tools:** Git, Chart.js (for reports)

---

### Prerequisites

* XAMPP/WAMP (Apache + MySQL + PHP)
* Git & Browser

### Setup

```bash
# Clone repository
git clone https://github.com/saurabhKrOO7/Tour-Travel-DBMS.git
cd Tour-Travel-DBMS
```

1. Start Apache & MySQL in **XAMPP/WAMP**
2. Create database `tour_travel_db` in **phpMyAdmin**
3. Import schema from `database/tour_travel_schema.sql`
4. Configure `config/database.php` with your DB credentials
5. Place project folder inside `htdocs/` (XAMPP)
6. Open in browser: `http://localhost/tour-travel-dbms/`

**Admin Panel:**

```
http://localhost/tour-travel-dbms/admin/  
Username: admin@traveldb.com  
Password: admin123  
```


---

## 🎯 Future Enhancements

* 📱 Mobile app version (React Native / Flutter)
* 🤖 AI-based travel recommendations
* 💬 Real-time customer support chat
* 🌐 Multi-language support
* 📊 Advanced analytics dashboard

---

<div align="center">  
  ⭐ If you found this project helpful, give it a star! ⭐  
  <br>Made with ❤️ by Saurabh Kumar  
</div>  

---

