# gitdone

Bash script that returns false when a local git repo isn't committed and pushed


Install: 
```
sudo cp gitdone /usr/local/bin
```


Primarily created for use in ansible:

```
---

- hosts: all

  tasks:

    - local_action: command gitdone
```
