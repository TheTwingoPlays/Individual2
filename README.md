# Individual use command in git bush

cd D:\gitIndividual - Перейди в папку проекта в git bush

git init - Подключаем к git gub

git remote add origin https://github.com/TheTwingoPlays/Individual2 - Ссылка на git hub

git pull origin main --rebase - Делаем что бы не было конфликтов

git branch -a - Проверяем появилось или нет

git add . - Добавляем файлы

git commit -m "project commit" - Делаем первый коммит

git pull origin main --rebase - Делаем перед пушем

git push -u origin main - Пушим на Git Hub

git checkout -b feat/add-transaction-api - делаем ветку

git commit -m "feat(api): implement transaction create endpoint" - Новый коммит

git push -u origin feat/add-transaction-api - Пуш ветки

<img width="573" height="379" alt="image" src="https://github.com/user-attachments/assets/eceac8a4-f6aa-4240-a254-1494d63a7a07" />

<img width="584" height="375" alt="image" src="https://github.com/user-attachments/assets/1299a79b-548e-4a32-a6bd-a8ba57b17b4c" />

<img width="586" height="377" alt="image" src="https://github.com/user-attachments/assets/3149cf73-19c5-41f8-bf2c-92d5d237093f" />

# IndividualProject
Project In Figma

https://www.figma.com/design/H5JqGUAtieg18wNfsf02Fr/INDIVID_DEKSTOP?node-id=22-5347&t=MIGiNx4Rq3ehKqwd-0

<img width="1316" height="920" alt="image" src="https://github.com/user-attachments/assets/1bdb53dd-b0e1-45d0-9382-fe13873f20f0" />

<img width="1330" height="916" alt="image" src="https://github.com/user-attachments/assets/e5a30da6-9a5e-424b-8488-731be7e8a5ad" />

<img width="1320" height="914" alt="image" src="https://github.com/user-attachments/assets/91d96202-f770-40ee-b15d-0c1cac95af46" />

<img width="1316" height="911" alt="image" src="https://github.com/user-attachments/assets/4fdaf2f9-6245-4b26-a34c-fc5a37351b52" />

<img width="1319" height="909" alt="image" src="https://github.com/user-attachments/assets/bc67c111-22b2-41ca-9a18-829e2914b972" />

<img width="1322" height="911" alt="image" src="https://github.com/user-attachments/assets/77302b81-cfa1-40a1-9fa3-0fa3588edac7" />

Функциональные требования (FR)

FR1 — Добавление транзакции: Пользователь может добавить транзакцию с полями: сумма, валюта, категория, тип (расход/доход), дата, заметка, метод оплаты.

FR2 — Редактирование транзакции: Изменение ранее введённых транзакций.

FR3 — Удаление транзакции: Удаление одной или нескольких транзакций.

FR4 — Просмотр списка транзакций: Сортировка и фильтры (по дате, категории, сумме).

FR5 — Категории: Добавление/редактирование/удаление категорий.

FR6 — Повторяющиеся транзакции: Настройка шаблонов для регулярных расходов/доходов.

FR7 — Отчёты: Генерация месячного отчёта (свод: общие расходы/доходы, разбивка по категориям, тренды).

FR8 — Экспорт/импорт: Экспорт отчётов в CSV/PDF; импорт/экспорт транзакций в CSV.

FR9 — Аутентификация (опционально): Логин/регистрация, восстановление пароля.

FR10 — Синхронизация/резерв: Резервное копирование и восстановление данных (облачный или локальный).

Нефункциональные требования (NFR)

NFR1 — Мультиплатформенность: Web (responsive), Android и iOS (или кроссплатформенный фреймворк — Flutter/React Native).

NFR2 — Производительность: UX без заметных задержек при работе с базой до 10000 транзакций.

NFR3 — Безопасность: Шифрование чувствительных данных в покое и при передаче (TLS); безопасное хранение паролей (хеш+salt).

NFR4 — Надёжность: Резервирование данных, возможность отката изменений (undo для удаления).

NFR5 — Локализация: Поддержка нескольких языков (RU/EN) и валют.

NFR6 — Доступность: Минимум WCAG AA (контраст, навигация с клавиатуры).

NFR7 — Конфиденциальность: Соответствие требованиям защиты данных (рекомендация: GDPR-совместимость, если требуется).

NFR8 — Тестируемость: Unit/Integration тесты для основных модулей (особенно финансовых расчётов).
