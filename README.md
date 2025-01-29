
# Local Installation

- run `` git clone https://github.com/NicholaCoding/triangle-pos.git ``
- run ``composer install `` 
- run `` npm install ``
- rename .env.example to .env
- run ``npm run dev``
- run `` php artisan key:generate ``
- set up your database in the .env
- run ''php artisan migrate''
- run `` php artisan migrate --seed ``
- run `` php artisan storage:link ``
- run `` php artisan serve ``
- then visit `` http://localhost:8000 or http://127.0.0.1:8000 ``.

> **Important Note:** "Triangle POS" uses Laravel Snappy Package for PDFs. If you are using Linux then no configuration is needed. But in other Operating Systems please refer to [Laravel Snappy Documentation](https://github.com/barryvdh/laravel-snappy).

# Docker Installation

This will start the application along with the mysql database using docker compose. Note that the `DB_HOST` variable must be the mysql docker container name, in this case `db`.

- run `` docker build -t triangle-pos . `` 
- run `` docker compose up ``
- then visit `` http://localhost:8000 or http://127.0.0.1:8000 ``.

Requirement:
Msql 
npm


# Admin Credentials
> Email: super.admin@test.com || Password: 12345678


## Inventory POS Features

- **Products Management & Barcode Printing**
- **Stock Management**
- **Make Quotation & Send Via Email**
- **Purchase Management**
- **Sale Management**
- **Purchase & Sale Return Management**
- **Expense Management**
- **Customer & Supplier Management**
- **User Management (Roles & Permissions)**
- **Product Multiple Images**
- **Multiple Currency Settings**
- **Unit Settings**
- **System Settings**
- **Reports**

