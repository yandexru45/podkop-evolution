# podkop-evolution → NetShift

> **Проект переехал и переименован в [NetShift](https://github.com/yandexru45/netshift).**

Этот репозиторий — **разовый мостик совместимости**. Уже установленные роутеры
проверяют обновления по старому адресу `podkop-evolution`, поэтому здесь
остаётся рабочий `install.sh`. Сам скрипт уже ставит **NetShift** и скачивает
пакеты из нового репозитория [`netshift`](https://github.com/yandexru45/netshift).

## Установка / обновление

Рекомендуемый адрес (новый репозиторий):

```sh
sh <(wget -O - https://raw.githubusercontent.com/yandexru45/netshift/refs/heads/main/install.sh)
```

Старый адрес (продолжает работать для уже установленных систем):

```sh
sh <(wget -O - https://raw.githubusercontent.com/yandexru45/podkop-evolution/refs/heads/main/install.sh)
```

Оба варианта ставят одно и то же — **NetShift**. Актуальная разработка и релизы:
**<https://github.com/yandexru45/netshift>**.
