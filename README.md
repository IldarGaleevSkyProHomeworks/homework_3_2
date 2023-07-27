# Задание 1
``` bash
cd /;ls > ~/root_files.txt
```

![Alt text](images/exercise1.png)

# Задание 2

``` bash
cd /usr/sbin/;ls *user*|sort > ~/user_cmd.txt
```
![Alt text](images/exercise2.png)
``` bash
ls /usr/bin/ /usr/sbin/|grep user|sort>user_cmd.txt
```
![Alt text](images/exercise2_1.png)

# Задание 3

``` bash
export MY_USER=user1
export MY_PASSWORD=passwd

echo $MY_USER:$MY_PASSWORD
```

![Alt text](images/exercise3.png)
``` bash
env|grep -P 'USER|MY|TERM'
```
![Alt text](images/exercise3_1.png)
# Задание 4

``` bash
cat <<EOF > file
#!/usr/bin/python3
print("Hello from Linux!")
EOF

chmod +x file
./file
```

![Alt text](images/exercise4.png)

``` bash
sudo apt install tree
tree
```

![tree_output](images/tree_output.png)