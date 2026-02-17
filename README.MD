### Добавление сразу всего листа на свой КВАС

```commandline
cd /tmp && curl -O https://raw.githubusercontent.com/avtotropa/KVAS-list/refs/heads/main/inside-kvas.lst && kvas import inside-kvas.lst
```

Далее обновляем таблицу правил iptables для vpn подключения: чистим ее и затем заполняем.

```kvas vpn reset```