# x64
## Инструкция по применению

1) Копируем библиотеку по пути(с заменой):
```
D:\steam\steamapps\common\GarrysMod\bin\win64
```
2) Создаём файл menu.lua в директории:
```
D:\steam\steamapps\common\GarrysMod\garrysmod\lua
```
3) В файл вставляем следующее:
```lua
wOS.ALCS.Skills:OpenSkillsMenu()
```
4) Заходим в игру, подключаем к серверу
5) В консоль вписываем команду
```
lua_openscript_cl menu.lua
```
