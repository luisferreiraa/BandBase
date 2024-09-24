# 🎸 BandBase - Manage Your Bands & Albums with Ease!

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)](https://github.com/luisferreiraa/bandbase/releases)

## 📖 Overview
**BandBase** is a sleek and intuitive application for managing your favorite bands and their albums. Whether you are tracking upcoming releases or simply keeping your collection organized, BandBase makes it easy to add, edit, and delete bands and albums, associating them seamlessly.

---

## 🎯 Features
- **Add Bands**: Easily add new bands to your collection.
- **Edit & Remove Bands**: Keep your band info up to date or remove bands no longer relevant.
- **Manage Albums**: Associate albums with their respective bands.
- **Simple & Intuitive UI**: Designed for smooth and efficient management of band and album data.

---

## 🚀 Getting Started

### Prerequisites
- [PHP 7.x](https://www.php.net/)
- [Laravel 9.x](https://laravel.com/)
- [MySQL](https://www.mysql.com/)
- [Composer](https://getcomposer.org/)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/luisferreiraa/bandbase.git

   ```
2. Navigate into the project folder:
    ```bash
    cd bandbase
    ```

3. Install dependencies:
   ```bash
   composer install
   ```

4. Set up the environment variables:
   ```bash
   cp .env.example .env
   ```

     Update the .env file with your database credentials.

5. Generate the application key:
   ```bash
   php artisan key:generate
   ```

6. Run the database migrations:
   ```bash
   php artisan migrate
   ```

7. Start the local development server:
   ```bash
   php artisan serve
   ```
## 🛠️ Usage
Once the app is running, navigate to http://localhost:8000 to access the interface. From there, you can:

- View all bands
- Add new bands
- Edit or remove existing bands
- View, add, edit, and delete albums associated with specific bands

## 🎨 Screenshots

## 🤝 Contributing
We welcome contributions! Please see our CONTRIBUTING guidelines for more details on how to get started.

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 📬 Contact
For any questions or suggestions, feel free to contact us:

- **Email:** luiscarneiroferreira@gmail.com
- **GitHub:** luisferreiraa
