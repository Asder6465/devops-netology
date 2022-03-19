# devops-netology

# Домашнее задание к занятию «2.1. Системы контроля версий.»

## Задание №1 – Создать и настроить репозиторий для дальнейшей работы на курсе. 

***/.terraform/* - игнорирует все файлы внутри каталога .terraform

В текущем каталоге игнорирует файлы служебные файлы.

====================================================
## Доработка домашнего задания

***/.terraform/* - игнорирует все файлы внутри каталога .terraform, созданного в локальной директории

Далее игнорируются все файлы состояния, имеющие расширение tfstate, а также если к этому расширению добавлено любое дополнение после точки.
Игнорируются файлы логов crash.log, в том числе и архивыне логи, имеющие дополнительное расширение, например crash.001.log
Также исключаются файлы, чувствительные к данным, например логины/пароли. Это файлы с расширением tfvars, а так же эти же файлы, преобразованные в json-последовательность
Игнорируется группа файлов override.tf, override.tf.json, а также под это определение попадают все файлы, имеющие в своем названии _override.tf bkb _override.tf.json
Ну и к игнору добавлены файлы .terraformrc и terraform.rc

