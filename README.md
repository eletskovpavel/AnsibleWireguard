# AnsibleWireguard
Это скрипт для установки wireguard 
Все очень просто для корректной работы необходимо следующее:
1. Установить ansible 
2. Сохранить скрипт в папку ~/ansible
3. Добавить нужный хост в файл inventory (обязательно укажите ansible_become_pass)
4. Сделайте отдельный файл с паролем (лучше всего воспользуйтесь ansible-vault)
5. Создайте конфиг wg0.conf с конфигурацией wireguard сервера 
6. Также создайте конфиги клиентов 
7. Запустите скрипт
8. Вуаля - вы великолепны
