1. Установка приложения. Создание Namespaces. Состояние Deployments, Pods:

![alt text](kub50.png)

2. Ошибка в логах Pods web:

![alt text](kub51.png)


3. Проверяем описание deployment web-consumer. curl без учета namespace data в котором расположен auth-db pod:

kubectl  describe deployments.apps -n web web-consumer

while true; do curl auth-db; sleep 5; done


![alt text](kub52.png)


4. kubectl  edit deployments.apps -n web web-consumer

while true; do curl auth-db.data; sleep 5; done


![alt text](kub53.png)