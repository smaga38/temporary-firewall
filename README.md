# temporary-firewall
Скрипт добавляет разрешающие правила iptables для транзитного трафика,
после того как истечет время, заданное в функции watchgog, правило удаляется.
Для изменения временного периода необходимо изменить значение в *function watchdog*, 
и изменить уведомление о временном периоде в *function agree*.

`# cp tempfw /usr/local/bin`

`# chmod +x /usr/local/bin/tempfw`

`$ sudo tempfw`
