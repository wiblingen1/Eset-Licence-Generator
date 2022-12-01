# ESET-Linense-Generator
ESET Linense Generator - Генерує акаунти для активації пробного періоду

# Як застосувати

0. Завантажити Microsoft Edge([https://www.google.com](https://www.microsoft.com/uk-ua/edge/home) та його Stable драйвер(https://developer.microsoft.com/uk-ua/microsoft-edge/tools/webdriver/). Драйвер потрібно розпакувати і перемістити в папку з main.py. Далі встановити бібліотеки Python:

pip install selenium, requests

1. Далі потрібно відредагувати main.py під ваші потреби.
SIZE - число (int) яке вказує скільки потрібно створити акаунтів
OUTPUT - текст (str) який вказує куди потрібно записати дані створених акаунтів
SLEEP - число (int) яке вказує затримку між операціями в секундах

2. Запустити main.py та зачекати до Press Enter...
Після цього в OUTPUT вас буде чекати файл із акаунтами.

3. Зайти в ESET і видалити поточний акаунт ESET HOME

4. Зайти на сайт ESET HOME через браузер та авторизуйтесь даними із OUTPUT файлу

5. В ESET клікніть Активувати повну версію продукту та авторизуйтесь даними із OUTPUT файлу
Далі в браузері зайдіть в розділ ліцензії, та видаліть поточну ліцензію

6. Поверніться в ESET, клікніть Активувати повну версію продукту та нажміть спробувати безкоштовно

# Рекомендації та інформація

1. Затримку SLEEP краще вибирати в межах 1-5 хв

2. Не створюйте багато акаунтів за короткий проміжок часу інакше вас заблокує сайт ESET HOME на певний час

3. Якщо програма зависла і не пише ESET Token це означає що вас заблокував ESET HOME
