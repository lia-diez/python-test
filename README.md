# Завдання
Засобами мови python необхідно завантажити дані з API (https://raw.githubusercontent.com/lia-diez/fake_json_data/main/fake_data.json) та CSV файлу (у директорії input даного репозиторію). Ці джерела симулюють 2 різних реєстри ведення обліку громадян. 
 
Необхідно вичленити такі дані про особу:
* ім'я
* прізвище
* дата народження
* стать
* номер телефону
* email
* номер паспорта з серією
  
— та записати їх в одну таблицю будь-якої реляційної БД на ваш вибір. Для спрощення розгортки можна використовувати SQLite. В результуючій таблиці номер телефону має бути в форматі +380ххххххххх, номер паспорта та серія зберігатися в одному полі, дата народження має бути в одному форматі.
 
Зверніть увагу, набори даних можуть містити NULL-ові значення. Ваш скрипт завантажте в репозиторій на свій GitHub, залежності запишіть в файл requirements.txt за допомогою команди ```pip freeze```.

### Додаткове завдання
При зверненні до API передавати в запиті header ```x-fake-auth``` із значенням ```YmlnIGJsYWNrIGNvY2s```
