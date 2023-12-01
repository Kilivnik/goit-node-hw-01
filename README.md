# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list

https://monosnap.com/file/ZnaunZdZOhzZUy7qNOrfZlr4wYP8Hy

# Получаем контакт по id - выводим в консоль объект контакта или null, если контакта с таким id не существует.

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6

https://monosnap.com/file/y7gTJKdmnl8WBzp78PYLCtlFFpE0JB

# Добавляем контакт и выводим в консоль созданный контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

https://monosnap.com/file/kcd5zLOM1ReXEYkaueSSAHMKc9gc8h

# Удаляем контакт и выводим в консоль удаленный контакт или null, если контакта с таким id не существует.

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH

https://monosnap.com/file/aFDkLR0GTv7xEtG2x3BxajKYlHSPzt
