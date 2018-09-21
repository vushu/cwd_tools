#### Preface
Im using the terminal alot especially navigating to different working dirs, but I got lazy doing that, 
so I made this simple tool to administrate your current working dirs to fastly switch from cwd to cwd.
Trust me this will save you some time, please enjoy :)

#### Getting it up running:
```
mkdir ~/tools && cd ~/tools && git clone https://github.com/vushu/cwd_tools.git

echo "source ~/tools/cwd_tools/cwd_tools" >> ~/.bashrc
source ~/.bashrc
```

#### Navigate to folder and to add to cwd-list or write path:
```
cwd-add
```
#### Show cwd-list:
```
cwd-list
```
#### Go to cwd 
```
cwd <number>
```
#### Show cwd path
```
cwd-get <number>
```
#### Remove cwd path
```
cwd-remove <number>
```
#### Show cwd-list.txt to manually modify
```
cwd-paths
```



