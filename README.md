# storage_gfs2

ДЗ Реализация GFS2 хранилища на виртуалках под виртуалбокс.

## На вашей выполняющей машине должны быть выполнены следующие действия:
* установить virtualbox 6.1
* установить vagrant (при необходимости настроить прокси сервер для работы vagrant)
* установить ansible
* скачать vagrant box https://cloud.centos.org/centos/7/vagrant/x86_64/images/CentOS-7-x86_64-Vagrant-2004_01.VirtualBox.box
* выполнить команду vagrant box add cent7 <путь до скаченного бокса>
* выполнить команду "git clone https://github.com/NexusPolarius/storage_gfs2.git"
* выполнить настройку параметров в файлах переменных nodes.yml и storage.yml, расположенных в /storage_gfs2/ansible/group_vars
* перейдите в каталог проекта storage_gfs2 и выполнить команду "vagrant up" 
* по окончанию создания виртуальных машин перейти в проекте в каталог ansible и выполнить команду "ansible-playbook main.yml"

