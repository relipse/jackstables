Welcome to Jack's Table Emporium
Installation
- application/db should have write permissions
- images/products should have write permissions
- go to application/config/config.php and change $config['base_url'] = 'http://jackstables.dev:8042/'; to the correct base url include trailing slash

Additional Comments
- Database should be MySQL since it is more strict with the data types, but sqlite was chosen for simplicity and small number of rows
- There should be a way to add multiple picture uploads, for example another table product_image pid image name
- There could be more product details such as pricing if we were to go with e-commerce and a shopping cart mechanism
- The admin page should have different user types and privileges such as add/delete/edit/view 
- The password should be hashed using PHP's password_hash() for the admin page and there should be a way to add admin users and change password etc.
- Ideally I would of been much more generic with everything instead of "Jack's Tables" but because this is going to be a fetch-and-go type of deal with minimal to no setup required, I just wanted to include all the configuration and database right in the project for that sake only.
- We could add pagination to admin/products and products page
- Category could be its own table and have a description, etc

