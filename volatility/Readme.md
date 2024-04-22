# Volatility #

> First we will get the volatility from the git-hub or the official page

![image](https://github.com/anandurdas11/CyberForensics/assets/83402050/09455937-40df-4dc9-90af-1b507726286f)

> First we will goto the Volatility directory and run the commannd
```
  sudo python2 vol.py -h
```
> We can use this command to get the list of commands that can be used.

![image](https://github.com/anandurdas11/CyberForensics/assets/83402050/f40e3e75-8ac3-4752-a977-9b23fa0435d1)

> We can use the command get the

```
    sudo python2 vol.py -f ../Bob.vmem imageinfo 
```

![image](https://github.com/anandurdas11/CyberForensics/assets/83402050/1d4dc6c4-28c3-4847-9ed8-43ca047fa9a6)

> We can see the list of the process in the memory sample using the command

```
    sudo python2 vol.py -f ../Bob.vmem pstree
```

![image](https://github.com/anandurdas11/CyberForensics/assets/83402050/d8d99a12-8a75-4d49-b7f7-85f2f5e42025)

> We can also list the no of open connection in the system using the following command

```
  sudo python2 vol.py -f ../Bob.vmem connections 
```
![image](https://github.com/anandurdas11/CyberForensics/assets/83402050/aa693298-e77d-491a-b889-dccbec388059)

> We can also view the list of command that were used by using the following  command

```
  sudo python2 vol.py -f ../Bob.vmem consoles
```
![image](https://github.com/anandurdas11/CyberForensics/assets/83402050/a71a39b1-b1d8-4112-8afd-b1854adb5b9e)
