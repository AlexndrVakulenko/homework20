# Домашнее задание:  Настройка PXE сервера для автоматической установки


Из Vagrantfile методички убран раздел provision поскольку скачивает файл iso большого объема из Internet.

Необходимые файлы необходимо скачать заранее по ссылкам в папку pxe_files:

https://old-releases.ubuntu.com/releases/24.04/ubuntu-24.04-netboot-amd64.tar.gz

https://old-releases.ubuntu.com/releases/24.04/ubuntu-24.04.1-live-server-amd64.iso


![Image alt](https://github.com/AlexndrVakulenko/homework20/blob/main/screenshots/01_pxe_files_dir.png)



Настройку pxe сервера выполняет файл work_pxe.yml



#### Проверка выполнялась созданием пустой vm в VirtualBox test с загрузкой по сети ####

![Image alt](https://github.com/AlexndrVakulenko/homework20/blob/main/screenshots/02_testVM_config1.png)


![Image alt](https://github.com/AlexndrVakulenko/homework20/blob/main/screenshots/03_testVM_config2.png)


#### Загрузка VM test с жесткого диска (otus/123) ####

![Image alt](https://github.com/AlexndrVakulenko/homework20/blob/main/screenshots/04_testVM_login_OK.png)
