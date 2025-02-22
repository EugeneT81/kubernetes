Task 1:
1. Применение манифеста Deployment. Состояние POD.

![alt text](kub4.png)

PVC not found:

![alt text](kub5.png)


2. Применение манифеста PV, PVC. Состояние POD - Running.

![alt text](kub6.png)

3. Удаление Deployment и PVC. Состояние PV.

"host_path deleter only supports /tmp/.+ but received provided /task2"

![alt text](kub7.png)


4. Файл на локальном хосте. Удаление PV. Проверка файла на локальном хосте.

![alt text](kub8.png)

5. Манифесты:

[Deployment](mydeployment.yml)

[PV](mypv.yml)

[PVC](mypvc.yml)



Task 2:

1. Применение манифеста Deployment. Состояние POD.


![alt text](kub10.png)


2. Применение манифеста PVC. Состояние POD.  

![alt text](kub11.png)

3. Манифесты:


[Deployment](mydeployment2.yml)

[PVC](mypvc2.yml)
