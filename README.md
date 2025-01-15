# cloud-ecommerce-project
# Cloud-Based E-commerce Project

## Overview
This project is a cloud-based e-commerce platform designed to offer a scalable, secure, and high-performance online shopping experience. It leverages AWS services for deployment and management.

## Features
- **User Roles:** Visitor, User, Admin
- **Product Management:** Admin can add, edit, and remove products
- **User Management:** Admin can manage user roles and details
- **Order Management:** Admin can process and ship orders with confirmation emails
- **Payment Methods:** PayPal, Stripe, Cash on Delivery
- **Wishlist, Product Comparison, and Flash Deals**
- **Secure Authentication** using AWS IAM

## Technologies Used
- **Backend:** PHP 8, Laravel Framework v9
- **Frontend:** HTML5, CSS3, Bootstrap v5.0
- **Database:** MySQL (AWS RDS)
- **Cloud Services:**
  - AWS Elastic Beanstalk (Deployment)
  - AWS EC2 (Hosting)
  - AWS IAM (Access Management)
  - AWS RDS (Database)
  - AWS S3 (Static File Storage)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```
2. **Install dependencies:**
   ```bash
   composer install
   npm install
   ```
3. **Configure environment:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
4. **Run the application:**
   ```bash
   php artisan serve
   ```
   Access at `http://localhost:8000`

## Project Structure
```
├── app/                  # Core Laravel files
├── bootstrap/            # Bootstrap files
├── config/               # Configuration files
├── database/             # Migrations and seeders
├── public/               # Public assets
├── resources/            # Views, CSS, JS
├── routes/               # Web and API routes
├── storage/              # Logs and uploads
├── aws/                  # AWS configs
├── .env.example          # Environment variables
├── .gitignore            # Git ignore rules
├── README.md             # Project documentation
└── composer.json         # Dependencies
```

## Deployment
1. **Deploy to AWS Elastic Beanstalk:**
   ```bash
   eb init
   eb create
   ```
2. **Set up RDS and S3 via AWS Console.**

## License
This project is licensed under the MIT License.

