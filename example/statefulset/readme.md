```
$ kubectl run -i --tty --image busybox:1.28.4 dns-test --restart=Never --rm /bin/sh
通过这条命令，我们启动了一个一次性的 Pod，因为 --rm 意味着 Pod 退出后就会被删除掉。
```