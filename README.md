# Developing Wordpress Locally
(Instructions summarized from https://codex.wordpress.org/Installing_WordPress_Locally_on_Your_Mac_With_MAMP)

- Install Homebrew (not really needed but useful)
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- Install MAMP
```
brew cask install mamp
```

- Open the MAMP app and press ```Start servers```, and then ```Open Webstart page```
- On the webpage search and click on ```phpMyAdmin```
- Press ```Databases```. In ```Create database``` enter ```wordpress``` as the database name (or any other name you wany, but remember it) and press ```Create```

- Download Wordpress and unzip folder
```
cd ~/Downloads
curl -O https://wordpress.org/latest.zip
unzip latest.zip; rm latest.zip
mv wordpress ~/Documents/mat3rial-dev/wordpress
```
- Open MAMP's preference, press ```Web Server``` and indicate the folder of your project (e.g., ```~/Documents/mat3rial-dev/wordpress```)

- Run Wordpress 5-minute installation by going in the browser to
http://localhost:8888

- Enter the following information or adapt it to your own configuration:

```
Database Name: wordpress
User Name (database): root
Password (database): root
Database Host/server: localhost
Table Prefix: wp_
```

- Start working ...
