# 🚀 PHP Swoole API Starter

A high-performance, lightweight backend starter kit built with **PHP 8.2 + Swoole** for creating fast and scalable REST APIs.

---

## 📌 Overview

**PHP Swoole API Starter** is designed for developers who want to build production-ready APIs with minimal setup. It provides a clean structure, essential features, and high concurrency support using Swoole.

---

## ⚡ Features

* ⚡ High-performance server powered by Swoole
* 🧱 Clean and modular project structure
* 🔐 JWT Authentication (ready to use)
* 📦 RESTful API architecture
* 🚀 Async & concurrent request handling
* 🛠 Environment-based configuration
* 📄 Ready-to-use API response format
* 🧪 Easy testing and debugging setup

---

## 🏗 Tech Stack

* PHP 8.2
* Swoole
* MySQL (or any supported DB)
* Composer

---

## 📂 Project Structure

```
├── app/
│   ├── Controllers/
│   ├── Models/
│   ├── Services/
│   └── Middleware/
├── config/
├── routes/
├── public/
├── storage/
├── .env
└── server.php
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/php-swoole-api-starter.git
cd php-swoole-api-starter
```

### 2. Install dependencies

```bash
composer install
```

### 3. Configure environment

```bash
cp .env.example .env
```

Update database and app settings in `.env`

---

### 4. Run the server

```bash
php server.php
```

Server will start at:

```
http://localhost:9501
```

---

## 🔐 Authentication

This starter includes basic **JWT authentication setup**.

Example:

```http
POST /api/login
```

---

## 📡 Sample API Endpoints

| Method | Endpoint    | Description    |
| ------ | ----------- | -------------- |
| GET    | /api/health | Health check   |
| POST   | /api/login  | User login     |
| GET    | /api/users  | Get users list |

---

## 🧪 Testing

You can test APIs using:

* Postman
* cURL

---

## 🌍 Use Cases

* REST API development
* Microservices backend
* High-performance applications
* Real-time systems

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub!

---

## 📬 Contact

For suggestions or issues, feel free to open an issue or connect.
