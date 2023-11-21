# hw-3-iscsi-vagrant
развернуть в VirtualBox следующую конфигурацию с помощью terraform

    виртуалка с iscsi
    3 виртуальные машины с разделяемой файловой системой GFS2 поверх cLVM
    должен быть настроен fencing для VirtualBox - https://github.com/ClusterLabs/fence-agents/tree/master/agents/vbox
    для сдачи
    terraform манифесты
    ansible роль
    README file



создаем конфиг, скачиваем заранее бокс файл для vbox, прописываем его в конфиге

для запуска деплоя выполнить vagrant up

для проверки статуса развернутых вм выполнить vagrant status

