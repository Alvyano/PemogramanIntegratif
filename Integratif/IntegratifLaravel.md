# PemogramanIntegratif

# Install Laravel- Pemograman Integratif

---
**Alvyano Rizqilla R - 1202190035**
---

### Install PHP

•	Download php on website https://windows.php.net/download#php-8.1. 

 ![](Gambar/1.PNG)


•	Then Extract the php file, find the file named `php.ini development`, rename the copy file to `php.ini`. after that open it using a text editor, and make it like in the picture, then save it.

  ![](Gambar/2.PNG)

  ![](Gambar/3.PNG)

•	Open `Edit The System Environment Variables`, click `Environment Variables`

   ![](Gambar/4.PNG)

•	Select the path variable to add the address of the php file earlier, then select ok.

  ![](Gambar/5.PNG)

  ![](Gambar/6.PNG)

•	Open a terminal and type `php –v`, it will display a screen as shown, which means that php has been successfully installed.

  ![](Gambar/7.PNG)
  
### INSTALL COMPOSER

•	Downlaod Composer https://getcomposer.org/download/

  ![](Gambar/8.PNG)

  
•	Install the composer file as usual. If you have opened a terminal and typed "composer", it will display a display as shown, where composer is already installed..

  ![](Gambar/9.PNG)

### INSTALL LARAVEL VIA COMPOSER

•	Create a project to install laravel with the command `composer create-project laravel/laravel name_project` and first go to the project folder that was created with the command `cd name_project/` And run the project with the command `php artisan serve`

![](Gambar/10.PNG)

•   Check Laravel installation in web browser

![](Gambar/13.PNG)

•	Copy laravel server, to open in browser
 
![](Gambar/11.PNG)

![](Gambar/12.PNG)

### Alvyano Rizqilla R - 1202190035

---
### **TAHAP 2 - RSS**
---

• Change DB_DATABASE in .env according to the database name created in phpmyadmin

![](Gambar/122.PNG)

![](Gambar/111.PNG)

• Create 2 tables rss and news with the migrations feature using the command

![](Gambar/133.PNG)

• Add the name and url columns to the rss table, as shown in the image below

![](Gambar/15.PNG)

• Add title, img_url, description, source_url, and rss_id columns to the news table, as shown in the image below

![](Gambar/14.PNG)

• To run the migration that was created, run the command in the terminal as below, then check the database

![](Gambar/16.PNG)

![](Gambar/17.PNG)

• Create model connection to database by creating seeders and controllers for Rss and News tables, with command

![](Gambar/18.PNG)

• Edit the Rss.php, RssSeeder.php and DatabaseSeeder.php files as shown in the image below

![](Gambar/19.PNG)

![](Gambar/20.PNG)

![](Gambar/21.PNG)

• Then check the connection with the command

![](Gambar/22.PNG)

• Edit the News.php file, News Controller.php, web.php, along with the News migration file as shown below

![](Gambar/24.PNG)

![](Gambar/25.PNG)

![](Gambar/26.PNG)

![](Gambar/27.PNG)

• Check localhost at http://127.0.0.1:8000/aggregrate/1 and in the phpmyadmin database

![](Gambar/28.PNG)

![](Gambar/29.PNG)

![](Gambar/30.PNG)

![](Gambar/31.PNG)

![](Gambar/32.PNG)

![](Gambar/33.PNG)

![](Gambar/34.PNG)

![](Gambar/35.PNG)

![](Gambar/36.PNG)

• Check localhost at http://127.0.0.1:8000/aggregrate/2 and in the phpmyadmin database

![](Gambar/38.PNG)

![](Gambar/39.PNG)

• Check localhost at http://127.0.0.1:8000/aggregrate/3 and in the phpmyadmin database

![](Gambar/40.PNG)

![](Gambar/41.PNG)

### **Alvyano Rizqilla R - 1202190035**
**HATUR NUHUN**

