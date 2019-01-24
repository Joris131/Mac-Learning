# Mac-Learning

## 01. 在 Mac 上的“终端”中纠正键入错误
## 02. mac rar 的使用
## 03. efetch install
## 04. 添加环境变量

## 01.在 Mac 上的“终端”中纠正键入错误

### 从光标位置清除到该行的开头：按下 Control-U 键。
### 从光标位置清除到该行的结尾：按下 Control-K 键。
### 在当前命令中重新定位光标：按住 Option 键，同时使用鼠标或触控板来重新定位光标。

## 02. mac rar 的使用

### rar a -ep1 新建归档.rar /Users/franklinli/Desktop/macos.txt /Users/franklinli/c++
#### #a          Add files to archive.
#### #-ep1       避免将整个路径都添加到压缩包。

## 03. efetch install

### sudo apt install acedb-other       
### sudo apt install ncbi-entrez-direct

## 04. 添加环境变量

    sudo vi ~/.bash_profile
### 添加变量：
    export PATH=/you/path/.../bin:$PATH    
### 保存后，执行：
    echo $PATH

