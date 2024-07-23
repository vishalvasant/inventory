![alt text](https://raw.githubusercontent.com/rpm192/Laravel-Inventory-Manager/master/public/img/branding/im-logo.png)
<hr>

![](https://img.shields.io/github/downloads/rpm192/Laravel-Inventory-Manager/total.svg?style=for-the-badge)
![](https://img.shields.io/github/license/rpm192/Laravel-Inventory-Manager.svg?style=for-the-badge)
<hr>

Inventory-Manager is an open-source stock / inventory management application based on the PHP-framework Laravel.

Currently, Inventory-Manager supports these features to help manage your inventory:

* Product management
* Stock management
* Storage location management
* Supplier management

Some of the key features of Inventory Manager:

* See which products are stored in which location
* Move products between locations in seconds
* Check stock in and out per location
* View which products every supplier supplies you

Features that are currently being implemented:

* See the total value of the inventory per storage location
* Multiple roles within the application to manage your employees
* Add customers to your system
* Create orders, with products and assign them to customers
* Manage the status of orders
* Update stock automatically after creating an order

## 🚀 Quick setup

Follow the steps below to get Inventory-Manager set up within minutes!

```
// clone this repository
git clone https://github.com/rpm192/Laravel-Inventory-Manager.git ./Inventory-Manager

// install the necessary packages
cd Inventory-Manager
composer install
```

After this, set up your database in the `.env` file!

```
// .env
DB_CONNECTION=mysql
DB_HOST=yourHost
DB_PORT=yourPort
DB_DATABASE=yourDB
DB_USERNAME=yourUser
DB_PASSWORD=yourPassword
```

To finish the setup, migrate and seed your database and generate an app-key!

```
// migrate the database
php artisan migrate:fresh
php artisan key:generate
php artisan db:seed
```

You can now login with the following credentials:

```
// user credentials
email: administrator@stockmanager.local
password: stockmanagerdefault
```
## 🔧 Bug reporting

Found an issue / bug? Want to report it? Please include __at least__ the following:

* Brief description of the issue
* An errorcode, if you have one
* The shortest amount of steps to reproduce the issue

If you have a possible solution / an idea what might cause the issue, feel free to include it.

__Please, do not request support if you're using an outdated version.__

## 💻 Credits

[AdminLTE](https://adminlte.io/themes/AdminLTE/index2.html) Inventory-Manager uses the front-end theme AdminLTE for the entirety of it's front-end.

## 📜 License

Inventory-Manager is open source and licensed under the MPL 2.0 license.

Inventory Manager &copy; 2019
