University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FTMI](https://fict.itmo.ru](https://ftmi.itmo.ru/ )  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)   
Year: 2024/2025  
Group: U4225  
Author: Kurakina Elizaveta Romanovna  
Lab: Lab1  
Date of create: 22.10.2024  
Date of finished: 22.10.2024  

# REPORT
## Task 1
Создаем сервисный аккаунт с ролью Storage Admin
![](/lab1/screenshots/image1)
## Task 2
Создаем минимальный compute engine с Machine type e2-micro в режиме spot  
![](/lab1/screenshots/image2)
## Task 3
Копируем файлы из бакета lab1-bucket-itmo к себе
![](/lab1/screenshots/image3)
## Task 4
Меняем роль сервисного аккаунта на Compute Viewer
![](/lab1/screenshots/image4)
## Task 5
Пробуем еще раз скопировать файл из бакета lab1-bucket-itmo
![](/lab1/screenshots/image5)  
Получаем ошибку, потому что теперь наш аккаунт не имеет достаточных прав. Установленная роль позволяет ему только просматривать файлы.
