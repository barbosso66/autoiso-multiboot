Инструкция.
1. Копируем файлы в $prefix вашего граба или в любую подпапку. У меня лежит в папке autoiso рядом с grub.cfg/
2. Добавляем пункт в меню своего grub.cfg (или что там у кого используется)

```
submenu "autoiso" {
configfile "${config_directory}"/autoiso/autoiso.cfg
}
```
Путь до autoiso.cfg правим на свой.
3. Копируем образы LiveCD в каталог /bootisos любого раздела.
4. reboot
https://archlinux.org.ru/forum/topic/19029/?page=1

original repo
https://github.com/jim945/autoiso-multiboot
