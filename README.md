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



### Day 3 Task: Basic Linux Commands

#### Task: What is the linux command to
```
1. To view what's written in a file.
2. To change the access permissions of files.
3. To check which commands you have run till now.
4. To remove a directory/ Folder.
5. To create a fruits.txt file and to view the content.
6. Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.
7. To Show only top three fruits from the file.
8. To Show only bottom three fruits from the file.
9. To create another file Colors.txt and to view the content.
10. Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.
11. To find the difference between fruits.txt and Colors.txt file.

```


# Solution

1. To view what's written in a file.
    - ``` cat filename ``` 
    
![3 1](https://user-images.githubusercontent.com/76457594/210305889-d19f82d5-dbb1-46fc-99e2-b217146b6e8a.png)



2. To change the access permissions of files.
   
    - ``` chmod 777 foldername ``` 

![Uploading 3.2.png…]()

3. To check which commands you have run till now.

   - ``` history ``` 

  ![Uploading 3.3.png…]()

4. To remove a directory/ Folder.

      - ``` rm filename ``` 
      
 ![3 4](https://user-images.githubusercontent.com/76457594/210308917-7281e0eb-6fcb-4554-8ffe-835cf0b961d1.png)

    -  ``` rmdir foldername ``` 
    
 ![3 4b](https://user-images.githubusercontent.com/76457594/210309299-367e6253-7e11-4ead-a19c-6eb3922780d1.png)

5. To create a fruits.txt file and to view the content.
    - ``` vim fruits.txt ``` 
    -  ```  cat fruits.txt ``` 
   
![3 5](https://user-images.githubusercontent.com/76457594/210311435-e6f8aa0c-dc0c-44a6-84e7-6e4c91e4ea87.png)


 
