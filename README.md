# Домашнее задание:  Настройка PXE сервера для автоматической установки


Из Vagrantfile методички убран раздел provision поскольку скачивает файл iso большого объема из Internet.

Необходимые файлы необходимо скачать заранее по ссылкам в папку pxe_files:

https://old-releases.ubuntu.com/releases/24.04/ubuntu-24.04-netboot-amd64.tar.gz

https://old-releases.ubuntu.com/releases/24.04/ubuntu-24.04.1-live-server-amd64.iso


![Image alt](https://github.com/AlexndrVakulenko/homework26/blob/main/screenshots/01_ipa_srv_install.png)

Настройку pxe сервера выполняет файл work_pxe.yml



#### Проверка выполнялась созданием пустой vm в VirtualBox test с загрузкой по сети ####

![Image alt](https://github.com/AlexndrVakulenko/homework26/blob/main/screenshots/01_ipa_srv_install.png)


![Image alt](https://github.com/AlexndrVakulenko/homework26/blob/main/screenshots/01_ipa_srv_install.png)


#### Загрузка VM test с жестког диска (otus/123) ####

![Image alt](https://github.com/AlexndrVakulenko/homework26/blob/main/screenshots/01_ipa_srv_install.png)