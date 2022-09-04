
## Configure Router-on-a-Stick Inter-VLAN Routing


### Задание:

   1. Build the Network and Configure Basic Device Settings
   2. Create VLANs and Assign Switch Ports
   3. Configure an 802.1Q Trunk Between the Switches
   4. Configure Inter-VLAN Routing on the Router
   5. Verify Inter-VLAN Routing is Working


### Решение:

   1. Прописать настройки обозначенными ТЗ на устройствах 
   2. Создать VLANs и прописать порты доступа обозначенными ТЗ на коммутаторах  
   3. Настроить транк порты между коммутаторами
   4. Настройка маршрутизации 
   5. Проверка работаспособности сети


#### Packet tracer diagram 
![image](https://user-images.githubusercontent.com/112641849/188316584-44baa9cd-cc02-4dd7-9b19-97dc9b9736af.png)

#### draw.io diagram 
![image](https://user-images.githubusercontent.com/112641849/188318192-32644653-a060-4665-9114-6b19bff8c6b5.png)


### Конфигурации:
   1. [R1](https://github.com/DlogNet/otus-networks/blob/main/labs/lab_4.2.8/configs/R1)
   2. [S1](https://github.com/DlogNet/otus-networks/blob/main/labs/lab_4.2.8/configs/S1)
   3. [S2](https://github.com/DlogNet/otus-networks/blob/main/labs/lab_4.2.8/configs/S2)

### Проверка средствами icmp:

PC-A -> GW

![image](https://user-images.githubusercontent.com/112641849/188320265-fade2463-58bb-4d5b-b557-91081fd3c144.png)

PC-A -> PC-B

![image](https://user-images.githubusercontent.com/112641849/188320435-1c171717-c089-4e4f-aa03-27449b0bd8ac.png)

PC-A -> S2

![image](https://user-images.githubusercontent.com/112641849/188320373-68ff9e1e-2101-4032-b368-2a3031476863.png)
