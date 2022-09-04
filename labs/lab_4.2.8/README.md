
## Configure Router-on-a-Stick Inter-VLAN Routing


### Задание:

   1. Build the Network and Configure Basic Device Settings
   2. Create VLANs and Assign Switch Ports
   3. Configure an 802.1Q Trunk Between the Switches
   4. Configure Inter-VLAN Routing on the Router
   5. Verify Inter-VLAN Routing is Working


### Решение:

   1. Прописать настройки обозначенными ТЗ на устройствах 
   2. Создать VLANs и прописать порты доступа обозначенными ТЗ на устройствах  
   3. Настроить транк порты между коммутаторами
   4. Настройка маршрутизации 
   5. Проверка работаспособности сети


#### Packet tracer diagram 
![image](https://user-images.githubusercontent.com/112641849/188316584-44baa9cd-cc02-4dd7-9b19-97dc9b9736af.png)

#### draw.io diagram 
![image](https://user-images.githubusercontent.com/112641849/188318192-32644653-a060-4665-9114-6b19bff8c6b5.png)


### Прописать настройки обозначенными ТЗ на устройствах

   ```
   hostname R1 \ S1 \ S2
   !
   !
   enable secret 5 $1$mERr$9cTjUIEqNGurQiFU.ZeCi1
!
!
no ip domain-lookup
!
!
banner login ^C

***************************************************************

*   ACCESS IS RESTRICTED TO AUTHORIZED USERS ONLY!            *

***************************************************************
!
!
line con 0
 password 7 0822455D0A16
 login
!
line aux 0
!
line vty 0 3
 login
line vty 4
 password 7 0822455D0A16
 login
!
!
```

   2. S1
   3. S2
