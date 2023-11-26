# Global_Warming_Project
Данный проект создан для того чтобы помочь борьбе с глобальным потеплением. На сайте проекта вы можете предлогать свои идеи по борьбе с глобальным потеплением.
Проект также предоставляет услуги дискорд бота при помощи которого вы можете узнать температуру в любом городе который только пожелаете.
Бот также способен различать 20 видов грибов на основе искусственного интеллекта.
## Скачивание библиотек
Для работы этого проекта вам необходимо установить некоторое количество библиотек
```bash
pip install TensorFlow pillow numpy flask flask_sqlalchemy requests SpeechRecognition PyAudio discord uuid
```
## Требования для корректной работы
### Запуск сайта
1. Скачайте архив с проектом и распакуйте его.
2. Удалите папку instance
3. Пропишите следующие команды в терминале:
    ```bash
    .\Scripts\activate.bat
    ```
    ```bash
    python
    ```
    ```bash
    from main import app, db
    ```
    ```bash
    app.app_context().push()
    ```
    ```bash
    db.create_all()
    ```
    ```bash
    quit()
    ```
    ```bash
    python main.py
    ```
    На этом этапе у вас должна была появиться ссылка на которую нужно перейти зажав клавишу ctrl и кликнув на ссылку левой кнопкой мыши. Поздравляю! Вы успешно запустили сайт. Дальше можете его исследовать.
### Запуск дискорд бота
4. Чтобы запустить дискорд бота нужно также прописать команды указанные выше, но вместо последней написать:
    ```bash
    python bot.py
    ```
    Но вам вряд ли будет полезна эта информация так как токеном от бота владею только я >:)
# Впрочем это всё что нужно знать! более подробную информацию вы получите во время использования проекта!
