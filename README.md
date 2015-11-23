# gitdone


Bash script that returns true only if the current directory is commited and pushed


Install: 

```
sudo cp gitdone /usr/local/bin
```

Created for use in ansible's local_action:


```
---

- hosts: all

  tasks:

    - local_action: command gitdone
```
