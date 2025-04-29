<b>University:</b> [ITMO University](https://itmo.ru/ru/) <br>
<b>Faculty:</b> [FTMI](https://ftmi.itmo.ru) <br>
<b>Course:</b> [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) <br>
<b>Year:</b> 2024/2025 <br>
<b>Group:</b> U4125 <br>
<b>Author:</b> Samedov Sultan Ilgar ogly <br>
<b>Lab:</b> Lab1 <br>
<b>Date of create:</b> 22.04.2025 <br>
<b>Date of finished:</b> 29.04.2025<br>

<h1>Отчет по лабораторной работе №1 </h1>
Описание заданий лабораторной работы можно найти здесь: https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/education/labs2023-2024/lab1/lab1/

1. Перейдем в раздел `IAM & Admin` на вкладку `Service Accounts`. Создадим сервисный аккаунт.
![image](https://github.com/user-attachments/assets/c3d297f7-d5e1-4fbd-8841-295e5296eca5)

2. Зададим нейминг аккаунта в соответствии с указанной в лабораторной маской. Перейдем к следующему шагу.
![image](https://github.com/user-attachments/assets/115d5c5e-8df3-4bf9-a674-b4f243510a28)

3. Выбираем роль `Storage Admin`. Сохраняем созданный аккаунт.
![image](https://github.com/user-attachments/assets/e7cdfdf3-64e8-4fea-8d1d-904fa1b6f566)

4. Теперь создадим и настроим виртуальную машину. Для этого перейдем в раздел `Compute Engine` на вкладку `VM instances` и нажмем на кнопку `Create instance`.
![image](https://github.com/user-attachments/assets/96219cff-97d8-45e6-8c5c-7db1787c061d)

5. Создадим машину со следующими параметрами (_при корректной настройке стоимость должна быть равна $3.44_):
![image](https://github.com/user-attachments/assets/39b6203f-f017-4421-915c-cf85d7294a93)
![image](https://github.com/user-attachments/assets/3c7fd4eb-f83f-47a3-a37f-cbb0bbc3bc1d)
![image](https://github.com/user-attachments/assets/f93725b8-b9cd-4f0d-af09-2eb8b43d1b0a)
![image](https://github.com/user-attachments/assets/c320f157-9b2f-4bd4-87b7-b25b2e3dd8c6)

6. Подключимся к созданной машине по SSH
![Uploading image.png…]()

7. В открывшемся окне введем команды для создания новой папки и копирования в нее заданных файлов. Закроем SSH-подключение.
![Uploading image.png…]()

8. Вернемся в раздел `IAM & Admin` на вкладку `Service Accounts`. Зададим новую роль `Compute Viewer` для сервисного аккаунта.
![image](https://github.com/user-attachments/assets/62a6c31e-6007-4f15-9bc4-5c69fe085451)
![Uploading image.png…]()

9. Снова запустим SSH-подключение. При попытке перенести данные на ВМ выдает следующую ошибку из-за отсутствия небоходимых прав
10. Удалим созданную ВМ и сервисный аккаунт.
