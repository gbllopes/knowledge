# Kill a process running in a particular port - linux

## Execute:

#### To list the PID of process:

```
$ fuser 8080/tcp
```

#### To Kill your process:

```bash
$ fuser -k 8080/tcp
```



