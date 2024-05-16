# Домашнее задание к занятию «Kubernetes. Причины появления. Команда kubectl»

### Цель задания

Для экспериментов и валидации ваших решений вам нужно подготовить тестовую среду для работы с Kubernetes. Оптимальное решение — развернуть на рабочей машине или на отдельной виртуальной машине MicroK8S.


### Задание 1. Установка MicroK8S

1. Установить MicroK8S на локальную машину или на удалённую виртуальную машину.

![alt text](img/1.png)

2. Установить dashboard.

![alt text](img/2.png)

3. Сгенерировать сертификат для подключения по ip-адресу.

![alt text](img/3.png)

![alt text](img/4.png)

------

### Задание 2. Установка и настройка локального kubectl
1. Установить на локальную машину kubectl.

```bash
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.goohleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
```
2. Настроить локально подключение к кластеру.

![alt text](img/5.png)

3. Подключиться к дашборду с помощью port-forward.

![alt text](img/6.png)

![alt text](img/7.png)

------

### Правила приёма работы

1. Домашняя работа оформляется в своём Git-репозитории в файле README.md. Выполненное домашнее задание пришлите ссылкой на .md-файл в вашем репозитории.
2. Файл README.md должен содержать скриншоты вывода команд `kubectl get nodes` и скриншот дашборда.

------

### Критерии оценки
Зачёт — выполнены все задания, ответы даны в развернутой форме, приложены соответствующие скриншоты и файлы проекта, в выполненных заданиях нет противоречий и нарушения логики.

На доработку — задание выполнено частично или не выполнено, в логике выполнения заданий есть противоречия, существенные недостатки.