# xmas-e-commerce


Пропишите в server и client ``` npm i ```

После в server .env пропишите правильно путь с паролем для своего postgresql ``` DATABASE_URL="postgresql://ВАШ_ПОЛЬЗОВАТЕЛЬ:ПАРОЛЬ@localhost:5432/ИМЯ_БАЗЫ?schema=public" ```

Затем ```npx prisma migrate dev --name init ```

И потом добавьте товары с файла seed.ts прописав: ```npm run seed  ```

Затем сначала запустите сервер командой ```npm run start ```, после забилдите клиент командой ```npm run build ``` и ``` npm run start ```. Готово
