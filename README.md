# pxeotus

## Задание 

Следуя шагам из документа https://docs.centos.org/en-US/8-docs/advanced-install/assembly_preparing-for-a-network-install установить и настроить загрузку по сети для дистрибутива CentOS8. В качестве шаблона воспользуйтесь репозиторием https://github.com/nixuser/virtlab/tree/main/centos_pxe.
Поменять установку из репозитория NFS на установку из репозитория HTTP.
Настройить автоматическую установку для созданного kickstart файла (*) Файл загружается по HTTP.
автоматизировать процесс установки Cobbler cледуя шагам из документа https://cobbler.github.io/quickstart/. Формат сдачи ДЗ - vagrant + ansible

## Решение

После развертывания стенда командой ```vagrant up``` наблюдаем при запуске pxeclient 

![image](https://user-images.githubusercontent.com/98832702/180188733-69ec9d70-ad3a-46ff-9b6a-2259b7d2dcfc.png)

Установка системы по сети происходит успешно. 
