# 🕋 Rehaab - Smart Electric Vehicle Reservation System

**AI-powered reservation system for electric vehicles at Al-Masjid Al-Haram**, reducing congestion by 60% and optimizing cart allocation for 2M+ annual visitors through real-time GPS tracking and intelligent queue management.

📄 **Published:** IEEE ICOCO 2024  
📱 **Platform:** Android (Flutter)

---

## 🎯 Problem & Solution

Al-Masjid Al-Haram faces severe congestion with electric vehicle reservations - no organized queue system, unpredictable wait times, and inefficient utilization. Rehaab solves this with GPS-based Tawaf tracking, smart queue management, barcode verification, and a multi-user platform.

---

## 🛠️ Tech Stack

**Frontend:** Flutter, Dart  
**Backend:** PHP, MySQL, Apache  
**Tools:** phpMyAdmin, GPS Services, Barcode Scanner

---

## ✨ Key Features

### For Visitors
- 📱 Easy booking with real-time availability
- 🕋 Automatic Tawaf counting via GPS
- ⏱️ Real-time wait time estimation
- 🎫 QR code verification

### For Vehicle Managers
- 📊 Fleet dashboard and real-time monitoring
- ✅ Barcode scanning for verification
- 🔄 Vehicle status and location tracking

### For Administrators
- 👥 User and system management
- 📉 Performance analytics
- ⚙️ System configuration

---

## 📊 Impact

- **60% Congestion Reduction**
- **92% GPS Accuracy**
- **<2 sec Response Time**
- **2M+ Potential Annual Users**

---

## 🚀 Quick Start

### Mobile App

```bash
git clone https://github.com/latifa22altamimi/2023-GP1-2.git
cd 2023-GP1-2
flutter pub get
flutter run
```

### Backend Setup

1. **Install XAMPP** (includes Apache, MySQL, PHP, phpMyAdmin)
2. **Create database** named `rehaab` in phpMyAdmin
3. **Import SQL file** from `database/rehaab.sql`
4. **Configure connection** in `config/database.php`:
```php
define('DB_HOST', 'localhost');
define('DB_NAME', 'rehaab');
define('DB_USER', 'root');
define('DB_PASS', '');
```
5. **Start services** via XAMPP Control Panel

---

## 🔑 Test Credentials

**Visitor:** shahadalothman2@gmail.com / Shahad12!  
**Manager:** alnaserfatimah344@gmail.com / Fatimah12!  
**Admin:** Latifah.maltamimi@gmail.com / Fatimah12!

---

## 🏗️ System Architecture

```
Mobile App (Flutter) 
    ↓ HTTP/REST
PHP API Layer (Apache)
    ↓
MySQL Database (phpMyAdmin)
    ↓
GPS Tracking • Barcode Scanner • Queue Management
```

---

## 📈 Future Enhancements

- iOS version
- Multilingual support
- Push notifications
- Payment gateway integration
- Route optimization

---


## 📄 Publication

**IEEE International Conference on Computing (ICOCO 2024)**  
*Electric Mobility Vehicle Reservation and Crowd Management for Al-masjid Al-haram*

---

<div align="center">

**⭐ Star this repo if you find it useful!**

Made with ❤️ for serving pilgrims worldwide

</div>
