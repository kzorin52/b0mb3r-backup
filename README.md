# b0mb3r-backup
К сожалению, эра b0mb3r закончилась. Вот его последняя версия...

> Я не несу ответственности за ваши действия. Скачивая программное обеспечение из этого репозитория, вы соглашаетесь с [лицензией](https://github.com/crinny/b0mb3r/blob/master/LICENSE).
# Установка
## На Windows
1. Установите Python версии не ниже 3.6, скачав установщик с [официального сайта](https://www.python.org/downloads/).
2. Установите git для Windows, скачав его [отсюда](https://git-scm.com/download/win).
3. Клонируйте репозиторий при помощи git и перейдите в папку:
    ```bash
    git clone https://github.com/kzorin52/b0mb3r-backup.git
    ```
    Распакуйте.
    ```bash
    cd b0mb3r-backup
    ```
4. Установите все необходимые библиотеки и запустите скрипт:
    ```bash
    pip install -r requirements.txt
    python main.py
    ```
5. Если в вашем браузере не открылся веб-интерфейс, перейдите по ссылке в консоли.

## На Android
1. Установите [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=ru)
2. Введите следующие команды поочерёдно для установки необходимых компонентов:
    ```bash
    pkg install python
    pkg install git
    ```
3. Выполните действия, начиная с пункта 3 из инструкции по установке на Windows.

# Обновление
## На Windows
1. Введите следующую команду для удаления предыдущей версии:
   ```bash
   rmdir /S /Q b0mb3r
   ```
2. Выполните действия, начиная с пункта 3 из инструкции по установке на Windows.
## На Android
1. Введите следующую команду для удаления предыдущей версии:
   ```bash
   rm -rf b0mb3r
   ```
2. Выполните действия, начиная с пункта 3 из инструкции по установке на Windows.
# Скриншоты
⁣                           |  ⁣
:-------------------------:|:-------------------------:
![](https://github.com/crinny/b0mb3r/blob/master/assets/screenshot.png)  |  ![](https://github.com/crinny/b0mb3r/blob/master/assets/screenshot_mobile.png)
