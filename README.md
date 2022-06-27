# biomack_infra
biomack Infra repository

## ДЗ-3 (cloud-bastion)

Данные для подключения:
```
bastion_IP = 51.250.102.165
someinternalhost_IP = 10.129.0.7
```

Подключение в одну строку:

```
ssh -i ~/.ssh/appuser -J appuser@51.250.102.165 appuser@10.129.0.7
```
