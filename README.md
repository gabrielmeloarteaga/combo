# Dropdown Dependent Combo on Codeigniter
This example shows three dropdown dependent combo, getting data from a mysql database.

How to install:

1. git clone https://github.com/gabrielmeloarteaga/dropdown-dependent-combo-codeigniter.git on your www folder in a web server.
2. Create a database on mysql called: dropdown
3. Modify the file on /application/config/databse.php:

  $db['default']['hostname'] = 'localhost';<br>
  $db['default']['username'] = 'your database username';<br>
  $db['default']['password'] = 'your database password';<br>
  $db['default']['database'] = 'dropdown';

4. Run script database-sample.sql on dropdown database
5. Load the app on the browser http://localhost/combo


