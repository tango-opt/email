# Сборщик email-рассылки

## Установка

- Скачайте и установите [NodeJS LTS](https://nodejs.org/ru/)
- Скачайте [файлы сборщика](https://github.com/tango-opt/email) во вкладке Code > Download ZIP
- Распакуйте архив
- Зажав Shift и кликнув правой кнопкой мыши в папке с распакованными файлами откройте командную строку
- Введите ```npm i```
- После успешной установки окно команд должно выглядеть примерно так:

![success]('https://raw.githubusercontent.com/tango-opt/email/main/installation/1.png')

## Использование

- Войдите в [foresty.io](https://app.forestry.io/dashboard/#/)
    *Если не получилось зайти в панель управления, залогиньтесь через Github и выберите в My sites email*
- На панели слева выберите пункт Data
- Измените необходимые для рассылки данные. Подробности о том, какое поле за что отвечает, здесь.
- Скопируйте содержимое [файла](https://raw.githubusercontent.com/tango-opt/email/main/src/_data/data.json) в файл ```email-main/src/_data/data.json``` **на компьютере**.
- Введите ```npm run build``` в командной строке
- В папке dist появятся результаты сборки: папка news – для ленты новостей на сайте, папка mail - для рассылки, папка web - для веб-версии письма.
