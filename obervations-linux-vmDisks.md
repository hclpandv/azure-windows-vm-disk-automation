## This is how a Linux VM disk looks like when we add one OS and one Data disk

#### Azure Portal

![image](https://user-images.githubusercontent.com/13016162/163542335-c2dcbe28-c35f-4178-a0f5-846e4bddfa1d.png)

#### Inside OS

`lsblk -o NAME,HCTL,SIZE,MOUNTPOINT | grep -i "sd"`

![image](https://user-images.githubusercontent.com/13016162/163542483-d7d329dd-d772-48f6-9e14-90d86e361256.png)

![image](https://user-images.githubusercontent.com/13016162/163543208-857346ae-d3d8-4b41-b65d-8bbb151db7b0.png)
