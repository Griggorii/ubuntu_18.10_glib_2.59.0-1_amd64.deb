# ubuntu_18.10_glib_2.59.0-1_amd64.deb
glib_2.59.0-1_amd64.deb ubuntu 18.10

&&cd ~/ && mkdir backup

&&cd /var/lib/dpkg/info/

&&sudo mv  'libglib2.0-dev:amd64.list' 'libglib2.0-dev:amd64.md5sums' 'libglib2.0-dev:amd64.prerm' 'libglib2.0-dev-bin.list' 'libglib2.0-dev-bin.md5sums' 'libglib2.0-dev-bin.postinst' 'libglib2.0-dev-bin.prerm' 'libglib2.0-bin.list' 'libglib2.0-bin.md5sums' ~/backup

&&dpkg -i glib_2.59.0-1_amd64.deb

Reboot

Не будет работать gnome-control-center в окружении ubuntu gnome , но этого не коснется budgie в нем будет работать как и ранее все кроме tilix терминала , а пока ничего другого не наидено сделано это не более как тест на скорость узнать будет ли быстрее работать. Из наблюдении в gtk оболочке наладилось то что пункты типа отмонтировать лешку стали отрисовываться с первого раза и полностью со всеми подпунктами хотя до этого надо было щелкать по два раза пкм прежде чем увидеть самый нижний пункт для отмонтирования накопителя.




