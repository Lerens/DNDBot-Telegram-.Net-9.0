# D&D Bot

## Опис (Description)
D&D Bot — це телеграм-бот, призначений для ведення партій по Dungeons & Dragons. Він дозволяє гравцям взаємодіяти з майстром, кидати кубики та вести ігрові дані.

D&D Bot is a Telegram bot designed for running Dungeons & Dragons sessions. It allows players to interact with the game master, roll dice, and manage game data.

## Можливості (Features)
- Генерація кидків кубиків (d20, d12, d10, d8, d6, d4)  
- Збереження інформації про персонажів  
- Ведення бази даних ігрових подій  
- Можливість взаємодії з ботом через чат-команди  

- Dice rolling (d20, d12, d10, d8, d6, d4)  
- Character information storage  
- Game event database  
- Interaction via chat commands  

## Вимоги (Requirements)
- .NET 8  
- Telegram Bot API  
- MSSQL 

- .NET 8  
- Telegram Bot API  
- MSSQL 


## Налаштування (Configuration)
Перед запуском вкажіть API-ключ бота у `App.config`

Before running, set the bot's API key in `App.config`
```
{
  "BotToken": "YOUR_TELEGRAM_BOT_TOKEN"
}

Також вам треба встановити майста (головного) вашої гри - MasterId та OwnerId - для різних функцій.
Для обох випадків, щоб правильно застосовувати команди вам треба застосувати команду "Додати інформацію до бота", всі команди ви знайдете у кнопці
"Допомога" і кнопках в клавіатурі.

You also need to set the master of your game - MasterId and OwnerId - for different functions.
In both cases, to apply commands correctly, you need to use the ‘Add information to bot’ command, all commands can be found in the
‘Help’ button and buttons in the keyboard.


```

## Використання (Usage)
Після запуску бота введіть команду `/start` в чаті з ним. Далі використовуйте доступні команди:

After starting the bot, enter `/start` in the chat. Then use the available commands. Now there are only Ukrainian laguage,
 but its possible in future to add English. 

Ви налаштували консольний додаток! Щоб використовувати DNDBot_GUI вам треба зробити ось такі кроки:
-Скомпілювати Консольний додаток у папку Public та впевнитись що є DNDBot.exe. 
-Зайти у проект DNDBot_GUI, у головний скрипт та замінити шлях на шлях до ДНД бота.
-Встановити NuGet package Fody: https://github.com/Fody/Fody
-Скомпілювати(у режимі отлатки)  DNDBot_GUI з вибраним "RELEASE", знайти додаток у файлах проекту.
- Для чого потрібен Fody? Щоб ви могли застосовувати DNDBot.exe без інших файлів!
Приємного користування

You have set up the console application! To use the DNDBot_GUI, you need to follow these steps:
-Compile the Console Application into the Public folder and make sure that DNDBot.exe is present. 
-Go to the DNDBot_GUI project, to the main script and replace the path with the path to the DND bot.
-Install the NuGet package Fody: https://github.com/Fody/Fody
-Compile (in debug mode) DNDBot_GUI with ‘RELEASE’ selected, find the application in the project files.
- What is Fody for? So you can use DNDBot.exe without other files!
Enjoy using it




Ліцензія (License)

This project is licensed under the MIT License.

Copyright (c) 2025 Yaroslav

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

For any inquiries, please contact:

Email: lorensstudio.it@gmail.com

GitHub: https://github.com/Lerens/It

Якщо є питання або пропозиції, створюйте issue або робіть pull request!

If you have any questions or suggestions, feel free to create an issue or submit a pull request!



Якщо є питання або пропозиції, створюйте issue або робіть pull request!

If you have any questions or suggestions, feel free to create an issue or submit a pull request!

