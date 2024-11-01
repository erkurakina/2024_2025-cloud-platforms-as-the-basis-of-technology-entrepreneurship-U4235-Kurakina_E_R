University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FTMI](https://fict.itmo.ru](https://ftmi.itmo.ru/ )  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)   
Year: 2024/2025  
Group: U4225  
Author: Kurakina Elizaveta Romanovna  
Lab: Lab3 4
Date of create: 2.11.2024   
Date of finished: 2.11.2024   
# REPORT  
В качестве исходных данных возьмем описание AI-приложения.  
Это AI-приложение для анализа трендов. Его функционал заключается в следующем: пользователь может задать свой запрос программе, указав временной промежуток, интересующую сферу, а также детальные фильтры, и AI-приложение вернет ему анализ трендов по заданным параметрам. Также пользователю доступны готовые графики, статьи и другие материалы по трендам в современном быстро развивающемся мире.  

Представим схему инфрастукртуры на примере запроса пользователя на анализ тренда с помощью диаграммы последовательности:  
![](/lab4/screenshots/image3)  

Будем использовать следующие сервисы Google Storage:   
API Gateaway - для того, чтобы принять запрос пользователя и отправить его далее в нужный компонент,  
APP Engine - для автоматического развертывания нашего приложения,  
BigQuery(SandBox) - для анализа (тренда) запроса по заданным фильтрам, 
CloudStorage - хранение данных, 
VM - запуск нашего сервиса.   




