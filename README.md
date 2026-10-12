# 🚗 RideMate — Smart College Ride-Sharing Platform

**Share the ride. Split the cost. Connect with your campus.**

RideMate is a smart college carpooling web application built with Flask and PostgreSQL that connects students who need a ride with students who have available seats. It makes daily college commuting easier, more affordable, and more convenient through a simple and secure platform.

## ✨ Key Features

- 🎓 **Student Authentication** — Secure registration and login.
- 🚘 **Driver & Passenger Roles** — Dedicated features for both drivers and passengers.
- 🛣️ **Offer a Ride** — Drivers can publish rides and available seats.
- 🔍 **Find Rides** — Discover available rides for your commute.
- 📅 **Ride Booking** — Passengers can request to book available rides.
- ✅ **Booking Management** — Drivers can accept or reject booking requests.
- 🔔 **Notifications & Status** — Keep track of booking updates.
- 👤 **User Profiles** — Manage personal account information.
- 🔐 **Security First** — Password hashing, CSRF protection, and secure session cookies.
- ⚡ **Production Ready** — PostgreSQL support, Gunicorn server, and health-check endpoint.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Flask | Web application framework |
| PostgreSQL / Supabase | Production database |
| SQLite | Local development database |
| HTML, CSS & JavaScript | Frontend |
| Gunicorn | Production application server |
| Render | Web application deployment |

## 🚀 Getting Started

**1. Clone the repository**
```bash
git clone <YOUR_REPOSITORY_URL>
cd RideMate
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Start the application**
```bash
python app.py
```

**4. Open in your browser**

http://127.0.0.1:10000

The application uses SQLite for local development when `DATABASE_URL` is not configured.

## ☁️ Deployment

RideMate can be deployed using:

- **GitHub** — Source code management
- **Render** — Web application hosting
- **Supabase** — Managed PostgreSQL database

Configure the required environment variables and follow `DEPLOYMENT.md` for production deployment instructions.

## 🔒 Security & Reliability

- Secure password hashing
- CSRF protection for POST requests
- Production secret-key validation
- Secure HTTP-only session cookies
- PostgreSQL-backed production data storage
- Application health monitoring through `/health`

## 🎯 Project Goal

RideMate aims to make college transportation more accessible by helping students coordinate rides, reduce individual commuting expenses, and connect with fellow students.

**Built for students. Designed for smarter commuting.** 💙

⭐ If you like this project, consider giving the repository a star!
