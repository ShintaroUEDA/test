# Linux Command #  
## compress and decompress ##  
### compress (xz file) ###  
tar -Jcvf ***file_name***.tar.xz ***file_name***  
- exclude file or directory  
tar --exclude *exclude_file_or_directory* -Jcvf *file_name*.tar.xz ***file_name***  

### decompress (xz file) ###  
tar -Jxvf *file_name*.tar.xz *file_name*  

### Options ###
### gz ###
- compress
tar -**z**cvf xxxx.tar.gz directory
- decompress
tar -zxvf xxxx.tar.gz
