# hyprland-config
конфиги hyprland, waybar, wofi и kitty

## Скриншоты

### Терминал
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/c08a00a3-a51c-4937-808f-17f113a10acf" />



### Меню пуск
<img width="1920" height="1080" alt="изображение" src="https://github.com/user-attachments/assets/2c065df8-e56f-4056-b793-323812a1f251" />



### Панель выключения
<img width="1280" height="960" alt="изображение" src="https://github.com/user-attachments/assets/b161cfe7-67f3-4c20-b857-6498da9981d8" />


### Значки верхней панели: Wifi, интернет и Bluetooth
<img width="1918" height="1078" alt="изображение" src="https://github.com/user-attachments/assets/e26b121a-2d77-405f-9dc7-6cc81d138791" />

Конфиг hyprland содержит переключение между русской и английской раскладками клавиатуры по Shift+Alt, закрытие окон по win+C, разворачивание по win+Z и win+X, а также по дополнительным кнопкам мыши *(321-323)*. Узнать название дополнительных кнопок на своей мыши можно с помощью утилиты wev.
Wofi: простое меню пуск, где можно искать и открывать приложения
Панели waybar: нижняя с приложениями и верхняя с раскладкой, настройкой интернета, вайфай и блютуз, изменением яркости и громкости, датой и временем и кнопкой выключения 


## Установка:

### Конфиги hyperland

Файл hyperland.conf переместить в *~/.config/hyprland*

### Панели waybar

1. Установить waybar командой:

   ```sudo pacman -S waybar```

2. Папку waybar переместить в ~/.config

### Wofi

   ``` sudo pacman -S wofi```
   
Папку wofi переместить в ~/.config

Изменить иконку меню можно в конфиге waybar *(197, 39)*, размеры в конфигах waybar *(198, 40)* и hyperland.conf *(46)* (по умолчанию ширина -- 33% экрана, высота -- 50%)

### Терминал kitty

Для включения прозрачности и блюра в *~/.config* переместить папку *kitty*

### Панель выключения wlogout

   ```sudo pacman -S wlogout```

Для локализации заменить файл layont в /etc/wlogout с помощью командой

   ```sudo mv ~/layont /etc/layont```
