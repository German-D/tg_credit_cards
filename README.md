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

## 💻 Технологии

* Python 2.0
* Библиотека `telebot`
* Библиотека `faker`

---

## ⏬ Установка на локальном компьютере

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
## Автор

Дольников Герман (Телеграм @dolnikov)
