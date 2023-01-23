# grub boot loader theme location

[file location of theme conf]

- /etc/default/grub
[themes folder and configuration entry for theme]

- GRUB_THEME=/boot/grub/themes/grubTheme/theme.txt

[Automation cmds]

- git clone https://github.com/moderncraft1234/grubTheme /boot/grub/themes/grubTheme

[after config]

- grub-mkconfig -o /boot/grub/grub.cfg


[Source]

- https://www.gnome-look.org/p/1972621
