
# Laravel-Vue CRM

This repository contains a CRM (Customer Relationship Management) application built with Laravel for the backend and Vue.js for the frontend. The project is designed to manage customer data, projects, and their relationships efficiently.

## Features

- **Customer Management**: Add, update, and delete customer information.
- **Project Management**: Create and manage projects and link them to customers.
- **Responsive Design**: Fully responsive UI to support various devices.
- **API Integration**: RESTful APIs for frontend-backend communication.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

### Backend (Laravel)

1. **Clone the Repository**

   ```bash
   git clone https://github.com/deshanlankal/Laravel-Vue-crm.git
   cd Laravel-Vue-crm/Back-End
   ```

2. **Install Dependencies**

   ```bash
   composer install
   ```

3. **Setup Environment**

   Copy the `.env.example` file to `.env` and update the environment variables as needed.

   ```bash
   cp .env.example .env
   ```

4. **Generate Application Key**

   ```bash
   php artisan key:generate
   ```

5. **Run Migrations**

   ```bash
   php artisan migrate
   ```

6. **Start the Laravel Server**

   ```bash
   php artisan serve
   ```

### Frontend (Vue.js)

1. **Navigate to Frontend Directory**

   ```bash
   cd ../Front-End
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Run Development Server**

   ```bash
   npm run serve
   ```

## Usage

- Access the Laravel backend API at `http://localhost:8000/api`.
- Access the Vue.js frontend at `http://localhost:8080`.

## Contributing

We welcome contributions to improve this project. To contribute:

1. **Fork the Repository**
2. **Create a New Branch**

   ```bash
   git checkout -b feature/your-feature
   ```

3. **Commit Your Changes**

   ```bash
   git add .
   git commit -m "Add your feature"
   ```

4. **Push to Your Fork**

   ```bash
   git push origin feature/your-feature
   ```

5. **Create a Pull Request**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Laravel**: The PHP framework used for the backend.
- **Vue.js**: The JavaScript framework used for the frontend.
- **Bootstrap**: Used for styling and responsive design.

---
