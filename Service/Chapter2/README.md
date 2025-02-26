Task 1:

1. Применение манифестов Deployment, SVC frontend and backend. Состояние PODs, SVC.

![alt text](kub20.png)

2. Проверка с помощью curl:

![alt text](kub21.png)

3. Манифесты:

[Frontend](deployment_frontend.yaml)

[Backend](deployment_backend.yaml)


Task 2:

1. Enable Ingress.

![alt text](kub25.png)

kubectl  apply -f Ingress.yaml 

2. Доступ с помощью браузера:

eugene@eugenek8s-client:~/kubernetes/kubernetes/Service/Chapter2$ more /etc/hosts | grep myi
192.168.1.200 myingress.service.ru 

http://myingress.service.ru

![NGINX](kub26.png)


http://myingress.service.ru/api

![MiltiTool](kub27.png)


3. Манифест Ingress:

[Ingress](Ingress.yaml)

