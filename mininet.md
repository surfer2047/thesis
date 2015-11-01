#Mininet installation testing

```bash
$ sudo mn --test pingall
$ sudo mn --test pingpair
```
for the documented help 

```bash
mn --help
```

##some basic commands in mininet

```bash

mn> help  #Display some help commands
mn> nodes #Display all the nodes controller, switch and hosts of the topology
mn> h2 ping h1 #Ping h1 from h2
mn> h2 ifconfig #Display the ip configuration of h2 host
mn> xterm h2  #Connect to the terminal of h2 host, where we can run all the commands

```