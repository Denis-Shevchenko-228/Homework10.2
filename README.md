# Homework 10.2
## Denis Shevchenko

### Решение первого задания:
```bash 
cd /
ls . > /home/denis/root_files.txt
```
![Первое задание](https://github.com/Denis-Shevchenko-228/Homework10.2/blob/main/assets/t1.png?raw=true)
---
### Решение второго задания:
```bash
cd /home/denis
ls /usr/sbin | grep 'user' | sort > user_cmd.txt
```
![Второе задание](https://github.com/Denis-Shevchenko-228/Homework10.2/blob/main/assets/t2.png?raw=true)
---
### Решение третьего задания:
```bash
export MY_USER=BimBom
export MY_PASSWORD=BamBam
echo $MY_USER
echo $MY_PASSWORD
```
![Третье задание](https://github.com/Denis-Shevchenko-228/Homework10.2/blob/main/assets/t3.png?raw=true)
---
### Решение четвертого задания:
```bash
sudo apt install python3
cat << EOF > file
#!/usr/bin/python3
print('Hello from Linux!')
EOF
sudo chmod 755 file
./file
```
![Четвертое задание 1](https://github.com/Denis-Shevchenko-228/Homework10.2/blob/main/assets/t4.1.png?raw=true)
![Четвертое задание 2](https://github.com/Denis-Shevchenko-228/Homework10.2/blob/main/assets/t4.2.png?raw=true)
---