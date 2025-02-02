
# Local Installation

- run `` git clone https://github.com/NicholaCoding/InventoryPOS.git ``
- run ``composer install `` 
- run `` npm install ``
- rename .env.example to .env
- run ``npm run dev``
- open new tab in terminal
- run `` php artisan key:generate ``
- run `` msql -u root -p
- insert your "password"
- run `` CREATE DATABASE triangle_pos; "(SQL)
- run ``exit;  ``(SQL)
- set up your database in the .env
- run ''php artisan migrate''
  
- run `` php artisan migrate --seed ``
- run `` php artisan storage:link ``
- run `` php artisan serve ``
- then visit `` http://localhost:8000 or http://127.0.0.1:8000 ``.

> **Important Note:** "Triangle POS" uses Laravel Snappy Package for PDFs. If you are using Linux then no configuration is needed. But in other Operating Systems please refer to [Laravel Snappy Documentation](https://github.com/barryvdh/laravel-snappy).



Requirement:
composer
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

