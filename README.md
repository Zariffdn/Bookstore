# Bookstore

A university team project: a PHP and MySQL bookstore with separate customer, seller and admin logins.

- Customers sign up, browse fiction and non-fiction titles, pay by card or cash, get a receipt and leave feedback.
- Sellers manage their listings and a pickup schedule for completed orders, which they can reschedule.
- The admin side lists every purchase.

## Running it locally

1. Create a MySQL database named `bookstore` and import `bookstore.sql`. The seed rows are sample data.
2. Check the connection settings in `config_db.php` and `conn.php`. They default to `root` on `localhost` with no password, which suits a local XAMPP install.
3. Serve the folder with PHP (for example from XAMPP's `htdocs`) and open `index.php` in a browser.
