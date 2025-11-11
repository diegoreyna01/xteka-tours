# 🌎 Xteka Tours – Django Web Application

**Xteka Tours** is a web platform for a travel agency built with **Django**.  
It allows clients to explore and book tour packages, while administrators can manage reservations, packages, and customer data through a secure dashboard.

---

## 🚀 Features

### 🧭 Client Side
- View available tour packages with detailed descriptions and prices  
- Make online reservations easily  
- Contact the agency through a dedicated form  
- Mobile-friendly interface  

### 🛠️ Admin Side
- Manage tour packages (create, update, delete)  
- View and control reservations  
- Manage clients and messages  
- Dashboard with key metrics and notifications  

---

## 🧩 Technologies Used

- **Django** (Python Framework)  
- **HTML5**, **CSS3**, **JavaScript**  
- **SQLite / PostgreSQL** (database)  
- **Django Admin** and custom dashboards  
- **Responsive UI** (custom CSS)

---

## ⚙️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/diegoreyna01/xteka-tours.git
   cd xteka-tours
   ```

2. **Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run the server**

   ```bash
   python manage.py runserver
   ```

6. **Access the app**

   - Client site: `http://localhost:8000/`  
   - Admin panel: `http://localhost:8000/admin/`

---


## 📂 Project Structure

```
xteka-tours/
│
├── xteka/                # Main Django project
├── tours/                # App for tour packages
├── reservations/         # App for managing bookings
├── static/               # CSS, JS, and images
├── templates/            # HTML templates
├── manage.py
└── README.md
```

---

## 🧑‍💻 Author

**Diego Reyna**  
Software Engineer  
📧 [GitHub Profile](https://github.com/diegoreyna01)

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it with attribution.


