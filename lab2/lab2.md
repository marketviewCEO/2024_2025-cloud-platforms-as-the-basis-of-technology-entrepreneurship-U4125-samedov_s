<b>University:</b> [ITMO University](https://itmo.ru/ru/) <br>
<b>Faculty:</b> [FTMI](https://ftmi.itmo.ru) <br>
<b>Course:</b> [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) <br>
<b>Year:</b> 2024/2025 <br>
<b>Group:</b> U4125 <br>
<b>Author:</b> Samedov Sultan Ilgar ogly <br>
<b>Lab:</b> Lab2 <br>
<b>Date of create:</b> 30.04.2025 <br>
<b>Date of finished:</b> 01.05.2025<br>

<h1>Отчет по лабораторной работе №2 </h1>
Описание заданий лабораторной работы можно найти здесь: https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/education/labs2023-2024/lab2/lab2/#_6

1. Создадим `Cloud Run` с минимальным количеством ресурсов из сервиса Hello
![image](https://github.com/user-attachments/assets/eb7a740a-7b39-4f97-8fa4-8ed1130a2421)

2. Перейдем по ссылке, предоставленной `Cloud Run`

3. Сервис работает корректно
![image](https://github.com/user-attachments/assets/7b96c570-db93-4df6-8cb8-22fe8ed6242d)

4. Перейдем в раздел `Logs`, проанализируем их
![image](https://github.com/user-attachments/assets/75fe1dac-75b5-4e45-80e9-cc34ea916a16)

5. Перейдем в раздел `Metrics`, проанализируем их
![image](https://github.com/user-attachments/assets/eb4ea82b-156a-41b3-bb3f-ae90f54e1b1f)

6. Поменяем порт на 8090 для нашего `Cloud Run`. Для этого нажмем на кнопку `Edit & deploy new revision` и заменим значение порта.
![image](https://github.com/user-attachments/assets/884f06cd-490e-40ca-9cd4-2106727231ce)

7. Отследим изменение метрик
![image](https://github.com/user-attachments/assets/f5a7ae75-6fb6-47d6-9caa-0959b3ea1a85)

8. Переключим трафик между версиями. Для этого вернемся в раздел `Revisions`, откроем контекстное меню `Actions` и выберем пункт `Manage traffic`.
![image](https://github.com/user-attachments/assets/3e750e1e-acf8-4654-a3c7-e7a30edacd60)

9. Зададим следующие параметры. Сохраним введенные значения.
![image](https://github.com/user-attachments/assets/c3c0837c-e0ca-427b-a47a-ecd675f4bd0b)

10. Отследим изменение метрик
![image](https://github.com/user-attachments/assets/7b81db7c-3c96-48d6-bfc3-4c09ad380fd1)

11. Удалим все созданные сервисы.
