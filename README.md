# devops_cicd
[![LINT-TEST-BUILD-CHECK](https://github.com/M0untain13/devops_cicd/actions/workflows/cicd.yml/badge.svg?branch=dev)](https://github.com/M0untain13/devops_cicd/actions/workflows/cicd.yml)
##
Работу выполнили Ракитин Арсений и Золотарёв Данил, группа ИТХ-2-2021.
##
1. Создаём само приложение:
   
   ![image](https://github.com/user-attachments/assets/4d40e9fc-75df-4750-84a3-e88c53159477)

2. Добавляем тестовый и боевой пайплайны:

   ![image](https://github.com/user-attachments/assets/be72dba0-305a-4f9f-9cd1-33f7d1e8084b)

3. В пайплайне pylint отключаем сигнатуры C0114, C0115, C0116, а также в приложении в функции take_five() заменяем 4 на 5.

   ![image](https://github.com/user-attachments/assets/a40fcfb2-0a6d-4526-86f8-24a1fb9b3c1b)

4. Для проверки работы пайплайнов добавим текстовый файл и сделаем коммит, а затем pull request. Приложение успешно прохоит все пайплайны.

   ![image](https://github.com/user-attachments/assets/e402febd-b53d-4df0-8beb-7ff53321c175)

5. Регистрируемся в докерхабе и создаём манифесты для куберизации приложения. В манифесте devops-psu указываем репо из докерхаба в качестве источника образа.

   ![image](https://github.com/user-attachments/assets/5dcc6fba-1f5e-4fe4-a644-4fcfab919ace)

6. Запускаем minicube и применяем наши манифесты.

   ![image](https://github.com/user-attachments/assets/a9e43355-3f05-4bfe-b305-8585998ff1a7)

7. Пробрасываем порты для сервисов LoadBalancer.

   ![image](https://github.com/user-attachments/assets/7077e97e-fee6-4860-adf7-cca1524f6bd7)

8. Сохраняем все манифесты в GitHub.
9. В докерхабе создаем токен доступа и записываем в секреты репозитория на GitHub вместе с именем пользователя.

    ![image](https://github.com/user-attachments/assets/5a6f6ba2-a802-4b77-a8eb-e1ce05894e99)

10. Создаём пайплайн для сборки и публикации образа в докерхабе.

    ![image](https://github.com/user-attachments/assets/2f359d87-dae6-48af-9eb3-c20107d1d2d3)

11. Как мы видим, пайплайн отработал и положил образ в докерхаб. Задача выполнена.

    ![image](https://github.com/user-attachments/assets/c00eb0d5-fc7c-45ab-ab43-dddd849583ef)
    ![image](https://github.com/user-attachments/assets/5851e172-09d7-449e-87f7-994cc8f4c7aa)







P.S мы нашли для вас идеальную футболку :)

![image](https://github.com/user-attachments/assets/453246d9-3a83-40af-9e4e-afcac924a979)







