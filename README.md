🏠 Estatio
> **Modern Open-Source Real Estate CRM built with Laravel 13, React & Inertia.js**
![Laravel](https://img.shields.io/badge/Laravel-13-red)
![PHP](https://img.shields.io/badge/PHP-8.3+-777bb4)
![React](https://img.shields.io/badge/React-19-61dafb)
![License](https://img.shields.io/badge/License-GPL--3.0-blue)
---

## 🖼️ Preview

<p align="center">
  <img src="./source/screenshot/dashboard-ui-1.jpg" width="100%" alt="Dashboard Preview 1" />
  <br><br>
  <img src="./source/screenshot/dashboard-ui-2.jpg" width="100%" alt="Dashboard Preview 2" />
  <br><br>
  <img src="./source/screenshot/dashboard-ui-3.jpg" width="100%" alt="Dashboard Preview 3" />
</p>

---
✨ Features

🏘️ Property management\
👥 Customer & lead management\
📅 Appointment management\
📊 Dashboard\
🔐 Authentication\
⚡ React + Inertia.js SPA\
🎨 Tailwind CSS\
🧪 Pest testing\
🎨 Laravel Pint\
🔍 Larastan\
🚀 Vite

---

🚀 Installation
```bash
git clone https://github.com/hirezadehghani/Estatio.git
cd Estatio

composer install
npm install

cp .env.example .env
php artisan key:generate
php artisan migrate

npm run dev
php artisan serve
```

🧪 Testing
```bash
php artisan test
```

🎨 Code Style
```bash
./vendor/bin/pint
```

🔍 Static Analysis
```bash
./vendor/bin/phpstan analyse
```

📚 Documentation

See:\
ARCHITECTURE.md\
ROADMAP.md\
CHANGELOG.md\
CONTRIBUTING.md\
SECURITY.md
---

🤝 Contributing
Pull requests are welcome! Please read CONTRIBUTING.md before opening one.
---

⭐ Support
If you like Estatio, please give the repository a ⭐ and share it with others.
---
📄 License
GPL-3.0
