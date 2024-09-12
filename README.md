# Домашнее задание к занятию «Управление доступом»

## Задание 1. Создайте конфигурацию для подключения пользователя

- Создаем ключ для подключения пользователя virus
  ![image](https://github.com/user-attachments/assets/f136c230-48d0-4bb1-b424-ba1cb2f8a19c)

- Настраиваем kubectl
  ![image](https://github.com/user-attachments/assets/00da6fd2-5b2c-4d1d-abc5-e85cfe0ed696)

- Включаем ролевую модель в microk8s и убеждаемся, что пользователю virus недоступны базовые действия
  ![image](https://github.com/user-attachments/assets/2fb85fd7-6dd4-4696-b834-d9d6244b52e9)

- Описываем роль и бинд роли в манифестах, возвращаемся в старый контекст, применяем роль и проверяем, что все корректно
  ![image](https://github.com/user-attachments/assets/b78e9e1e-bc4a-433e-8bf5-288118187cb9)
  ![image](https://github.com/user-attachments/assets/eab8e2b6-a802-4e1b-803a-edd67981825c)

- Возвращаемся в контекст test-context и проверяем права
  ![image](https://github.com/user-attachments/assets/0ebfceae-cbf1-4c1a-bcec-f19f54c3b027)
  ![image](https://github.com/user-attachments/assets/d25db9ac-568f-44d8-bf79-628c8c79c2e5)
