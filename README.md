# hyprland-config
конфиги hyperland, waybar, wofi и kitty с поддержкой русской раскладки

## Скриншоты

### Дизайн панелей
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/1f8a8b7a-2098-4040-96be-e0049743486f" />

### Меню пуск
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/477d19b2-abd0-4a7b-a125-635f9dbe6029" />

### Прозрачный терминал kitty
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/64cc1c3c-0469-4213-bfdf-7c8078a3abf5" />

### Панель выключения
<img width="1280" height="960" alt="изображение" src="https://github.com/user-attachments/assets/b161cfe7-67f3-4c20-b857-6498da9981d8" />

## Конфиги hyperland
Файл hyperland.conf переместить в ~/.config/hyprland
Содержит переключение между русской и английской раскладками клавиатуры по Shift+Alt
Открытие меню пуск по кнопке win, закрытие окон по win+C, разворачивание по win+Z и win+X, а также по дополнительным кнопкам мыши *(321-323)*. Узнать название дополнительных кнопок на своей мыши можно с помощью утилиты wev

## Панели waybar
1. Установить waybar если он ещё не установлен:
   '''sudo pacman -S waybar'''

2. Папку waybar переместить в ~/.config

## Wofi
Wofi -- простое меню пуск, где можно искать и открывать приложения.

### Установка:
   ''' sudo pacman -S wofi'''
Папку wofi переместить в ~/.config

Изменить иконку меню можно в конфиге waybar *(197, 39)*, размеры в конфигах waybar *(198, 40)* и hyperland.conf *(46)* (по умолчанию ширина -- 33% экрана, высота -- 50%)

## Терминал kitty
Для включения прозрачности и блюра в ~/.config переместить папку kitty 
## Панель выключения wlogout
### Установка:
'''sudo pacman -S wlogout'''
Для локализации заменить файл layont в /etc/wlogout с помощью sudo mv
