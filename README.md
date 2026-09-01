<img width="373" height="80" alt="IDE_Compiler" src="https://github.com/user-attachments/assets/b4665a90-ff7a-4756-a6ae-075c2d0adea8" />

[![Latest Version](https://img.shields.io/github/release/leserg73/IDE_Compiler.svg)](https://github.com/leserg73/IDE_Compiler/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/leserg73/IDE_Compiler/total.svg)](https://github.com/leserg73/IDE_Compiler/releases)
[![Latest Release Downloads](https://img.shields.io/github/downloads/leserg73/IDE_Compiler/latest/total.svg)](https://github.com/leserg73/IDE_Compiler/releases/latest)

# IDE компилятора
### (Среда разработки и компиляции сценариев Inno Setup)
____


Начиная с версии 7.1.0 в редактор и компилятор сценариев Inno Setup (программный модуль **ISIDE.exe**) была добавлена языковая поддержка. Интерфейс программы стал доступен на *немецком*, *японском*, *чешском* и *голландском* языках, который можно выбрать в настройках. Языковые файлы встроены в код программы и их невозможно отредактировать без полной пересборки файла программы. Также разработчик заявил, что не принимает заявки на добавление других языков:

> The translations cannot be edited, and additional languages are not being accepted.


Странное заявление... При том, что для следующей версии языковая поддержка расширяется.
На мое предложение с добавлением русского и украинского разработчик ответил категорическим отказом.

Раз нет - сделаем сами.

Здесь представлена частная сборка файла **ISIDE.exe**, в котором добавлены русский и украинский языки.

Файлы сообщений:
* IDE.LocalizeFunc.Russian.pas
* IDE.LocalizeFunc.Ukrainian.pas


Загрузите архив из раздела релизов. В архиве находятся 32-/64-разрядная версии файлов программы. Скопируйте файл соответствующей разрядности в каталог с установленной Inno Setup и подтвердите замену оригинального файла. Предварительно можно сделать резервную копию исходного файла или просто переименовать его.

После запуска перейдите в настройки программы и выберите язык интерфейса: русский или украинский. Перезапустите программу, чтобы сделанные изменения вступили в действие. Имейте в виду, что языковые файлы касаются только интерфейсной части приложения. Все сообщения компилятора и отладки будут на английском языке.


____

Справка на русском языке в формате [CHM](https://github.com/leserg73/InnoHelp/releases) для различных версий Inno Setup.
