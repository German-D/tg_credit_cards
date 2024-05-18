<h2>Телеграм бот, который генерирует номера банковских карт</h1>

> **Статус сервиса:**
>
> 🟢 Поддерживается (активный) 

---

## Цели и Задачи
Помочь QA инженеру быстро получить нужный номер карты при тестировании в тестовой среде.

Бот геренирует номера тестовых банковских карт:
* Номера карт проходят проверку на алгоритм Луна
* Можно получить номер карты: Visa, Maestro, Mastercard, JCB

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/German-D/tg_credit_cards/main/bot_menu.png)

После выбора карты Visa:

![image](https://raw.githubusercontent.com/German-D/tg_credit_cards/main/visa_card.png)

---

# 💻 Технологии

* Python 2.0
* Библиотека telebot
* Библиотека faker

---

# ⏬ Установка на локальном компьютере

Клонируем удалённый репозиторий на локальную машину:

```markdown
git clone git@github.com:German-D/tg_credit_cards.git
```
Устанавливаем все необходимые компоненты:

``` markdown
pip install pyTelegramBotAPI
```

``` markdown
pip install faker
```
---
Содержание файла "docker-compose.yml":

![image](https://github.com/Nico-kun123/EShop-Parser/assets/77405288/5144d052-5d72-4fc3-a2f1-6f5b577079bc)

Для запуска базы данных нужно ввести в терминале следующее:
> **Примечание:** Предусмотрено, что на вашем устройстве установлен Docker.
```markdown
docker-compose up -d
```
...а для выключения:
```markdown
docker-compose down
```
---
Содержание "package.json":

![image](https://github.com/Nico-kun123/EShop-Parser/assets/77405288/4cbbc681-c4ae-4712-8073-8e4fe5f40acf)

В проекте есть следующие скрипты:

![image](https://github.com/Nico-kun123/EShop-Parser/assets/77405288/2864fbc1-a13f-4ccf-9db2-3c178ba2a1ef)

- "build". Запускает транскомпилятор "Babel" для сервера;
- "start". Запускает скрипт "build", затем — сам сервер;
- "parser". Запускает модуль-сборщик данных.
---
## Автор

Кудрявцев Николай (Электронная почта: nicolay.kudryavtsev@gmail.com)
