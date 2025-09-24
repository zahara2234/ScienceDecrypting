# ScienceDecrypting
ScienceDecrypting包，提供exe，python源码和支持批量解密的bat脚本
## Usage

### 选择一：使用预编译的exe文件

使用包内的ScienceDecrypting.exe，打开后选择单个要解密的文件，自动在目标的文件夹下生成解密后的文件，exe程序可单独使用，无其它依赖项

### 选择二：使用bat脚本(间接调用python脚本)

1. 下载安装Python3 ( https://www.python.org/downloads/ )。
2. 运行installrequirements.bat安装依赖
3. 将目标文件置于books文件夹中，运行decrypt.bat，自动在decrypt_books文件夹中生成解密后的文件，文件名与解密前相同

### 选择三：使用python源码

decrypt.py为源码文件，可参考Reference.md进行使用
