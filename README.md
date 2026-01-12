#Тестовое задание для компании Intec

## Требования
Перед запуском проекта убедитесь, что у вас установлены:
-PostgreSQL
-Node.js
-npm
-IntelijIDEA

## Настройка бд через pgAdmin или через консоль
-Требуется создать Database testIntec
И таблицу:
CREATE TABLE intervals(
  id BIGSERIAL PRIMARY KEY,
  "start" INT NOT NULL,
  "end" INT NOT NULL,
  type VARCHAR(10) NOT NULL
);


##Запуск frontend
Перейдите в корневую папку проекта, а точнее в папку frontend.
Введите следующие команды
-npm install
-npm run dev

После успешного запуска у вас должно появится сообщение:  
VITE v4.5.14  ready in 822 ms
  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help

## Запускайте backend через IDE и переходите на URL http://localhost:5173/
