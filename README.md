# Linux_basics


## Architecture of Linux

![LINUX Arch](https://github.com/DhanashriSaner/Linux_basics/assets/88526990/15cf1244-facf-43e1-9706-dde2f62f7394)

## Commands for Ubuntu

#### 1) Create new Directory(folder)

```
mkdir new_folder
```
#### 2) List files and directories.

```
ls
```
#### 3) return the username

```
whoami
```
#### 4) What is the default location of log files in Linux? 

```
/var/log
```
#### 5) Present Working Directory 

```
pwd
```
#### 6) Kernel Name

```
uname
```
#### 7) allows you to temporarily elevate your current user account to have root privileges. 
**sudo** stands for super user do

```
sudo
```
#### 8) Switch to root user
**su** stands for **switch user** or **substitute user**
**su** means to switch to a particular user
```
sudo su
```
#### 9) delete directory(folder)

```
rm -rf new_folder/
```

#### 10) touch command to create a new file
```
touch my_file.txt
```
#### 11) Delete file my_file.txt

```
rm my_file.txt
```
#### 12) Display a line of text that is passed in as an argument.

```
echo "Hello"
```
#### 13) Display a line of text that is passed in as an argument in the file.

```
echo "Hello" > my_file.txt
```
#### 14) To see the data inside the file.

```
cat my_file.txt
```

#### 15) vim command to create a new file

```
vim new_file.txt
```

#### 16) To save the changes and exit from vim
**wq** stands for write & quite
```
:wq
```
#### 17) To get a full list of hidden files

```
ls -la
```

#### 18) create a file 'test' and insert the content inside file

```
touch test && echo "This is DevOps class file"
```
#### 19) to jump on previous directory

```
cd ..
```
#### 20) Create 10 files using one command
```
touch file{1..10}.txt
```
#### 21) Move any file which starts with 'file' name into the devops folder
```
mv file* devops/
```
#### 22) To view the previously executed command
```
history
```






