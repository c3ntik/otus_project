# otus_project

### Тема: "Развёртывание web-проекта wordpress и сервисной инфраструктуры, используя Ansible"

Репозиторий содержит следующие директории:
- ANSIBLE - Автоматизация развертывания инфраструктуры

### Используемое ПО
- В качестве web-проекта был выбран бесплатный wordpress.
- В качестве хранилища данных для wordpress выбор остановился на базе данных MySQL
- В качестве системы мониторинга был выбран Zabbix Server версии 6.2 и агенты мониторинга Zabbix Agent 2
- В качестве системы логирования был выбран стандартный Rsyslog
- В качестве системы резервного копирования были выбраны Rsync (резервное копирование файлов) и Pg_Basebackup (Резервное копирование PostgreSQL)

### Схема проекта

![SCHEME](/SCHEME.png)

### Итог playbook

![proc](/proc.png)

### Запуск Zabbix

![zabbix](/zabbix.png)

### Запуск WordPress

![wp](/wp.png)


