```
cprm(){
    cp -p $1 ~/deleted/$1
    rm $1
}
```

```
cprm(){
    mv $1 ~/deleted/$1 
}
```


```
$ sudo apt-get install trash-cli
$ alias rm=trash
```

[用GitLab搭建自己的私有GitHub](http://segmentfault.com/a/1190000000345686)