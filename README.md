# hyprland-config
конфиги hyperland, waybar, wofi и kitty с поддержкой русской раскладки

## Скриншоты

### Дизайн панелей
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/acc5b5bc-40c3-49ad-9449-f86759e9f698" />


### Меню пуск
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/2bf2b70f-b458-4c8d-96a7-b51887e40c34" />



### Панель выключения
<img width="1280" height="960" alt="изображение" src="https://github.com/user-attachments/assets/b161cfe7-67f3-4c20-b857-6498da9981d8" />


###Значки верхней панели: Wifi, интернет и Bluetooth
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/5d8218dc-6756-4f97-9627-d3afc702e860" />


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
