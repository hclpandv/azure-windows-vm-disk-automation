## This is how it looks when you add a new Data Disk on Running Azure VM (No reboot)

#### Azure Portal

![image](https://user-images.githubusercontent.com/13016162/163523613-7d2dc8f9-fbc0-412f-8754-83b3d4b82c53.png)

#### Inside OS (Immidiately/Without reboot on a running VM)

![image](https://user-images.githubusercontent.com/13016162/163523752-87b21d20-6ccb-42d0-91a8-c5a4e425c87e.png)

![image](https://user-images.githubusercontent.com/13016162/163523915-552edd37-b20e-437f-815f-c771f28541c3.png)

![image](https://user-images.githubusercontent.com/13016162/163524306-5b6072e9-6568-4022-8dab-7f90736eac82.png)

#### Update

Define `partition style` while initializing the disk `Initialize-Disk -Number 3 -PartitionStyle MBR`

#### Final Output

![image](https://user-images.githubusercontent.com/13016162/163524444-12871740-4699-4b91-991f-0021f1f90e64.png)
