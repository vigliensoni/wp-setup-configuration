# Developing Wordpress Locally
(Instructions taken from https://codex.wordpress.org/Installing_WordPress_Locally_on_Your_Mac_With_MAMP)

- Install Homebrew.
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- Install MAMP
```
brew cask install mamp
```

- Open MAMP and go to Preferences, click Web Server and Select to indicate the folder of your project (e.g., ~/Documents/mat3rial-dev/wordpress)
- Start the MAMP servers (button on the main app screen), and open Webstart page
- On the webpage search and click on phpMyAdmin
- Press 'Databases' and 'Create database'
- Enter 'wordpress' as the database name and press 'Create'

- Download Wordpress and unzip folder
```
cd ~/Downloads
curl -O https://wordpress.org/latest.zip
unzip latest.zip; rm latest.zip
mv wordpress/ ~/Documents/mat3rial-dev
```
- Run Wordpress 5-minute installation by going in the browser to
http://localhost:8888

- Enter the following information

Database Name: wordpress
User Name (database): root
Password (database): root
Database Host/server: localhost
Table Prefix: wp_
