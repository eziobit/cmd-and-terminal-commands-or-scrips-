# cmd-and-terminal-commands-or-scrips
### cmd cool commands:

##### 1 color change
this will change color of command prompt this first character will effect backgrout while second to text color 
``` 
color 02 
```

##### 2 change title

This will cange the title in top bar of command prompt
```
title hello
```

##### 3 change prompt type;
``` 
prompt kali@klai

help prompt         //for special letter

``` 


##### 4 hide folder
```
attrib +h +s +r foldername  //hide_folder
attrib -h -s -r foldername  //show_folder
help attrib                 //help_for_attrib

```
##### 5 copy output of a command:
this command will copy output of command on clipboard you can past anywhere in any file.
```
command | clip
```
##### 6 create file with echo 
``` 
echo > filename.txt   // to carete a file 
echo this text will be witten in file > filename.txt   // to write a file
type >filename.txt  //this line will fetch text from file.
``` 

##### 7 take ownership of file or folder

```
takeown /R  /F  C:\windows\etc\xyz
```
