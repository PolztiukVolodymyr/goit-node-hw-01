Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
https://monosnap.com/file/dL0Y68mfbemvOWapKkPuxEhA5Rfndo

<!-- ------------------------------- -->

Отримуємо контакт по id
node index.js --action="get" --id=5
https://monosnap.com/file/qgKKKMoLjB2W2OO1IBVqcGxXjX6950

<!-- --------------------------------- -->

Добавляємо контакт
node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22"
https://monosnap.com/file/EddfcHltuXaDPi0qyV7hif4ZIeWR8y

<!-- ---------------------------------------- -->

Видаляємо контакт
node index.js --action="remove" --id=3
https://monosnap.com/file/iBGg9v1aROF0UWCdFpcgmPrR2cj45p
