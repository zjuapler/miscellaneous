
## 1 Python 不换行输出

```python
for i in range(100):
    print '%d\r'%i,
```

## 2 shell 不换行输出
```shell
i=0
while [[ $i -lt 10 ]]
do
    i=$(xxxxxxx)
    a=.$a
    printf "Waiting%-100s\r" $a
    sleep 3
done
```
