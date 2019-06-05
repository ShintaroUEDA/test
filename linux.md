# Linux Command #  
## compress and decompress ##  
### compress (xz file) ###  
tar -**J**cvf *file_name*.tar.xz *directory*  
- exclude file or directory  
tar **--exclude** *exclude_file_or_directory* -Jcvf *file_name*.tar.xz *directory*  

### decompress (xz file) ###  
tar -**J**xvf *file_name*.tar.xz  

### Options ###
### gz ###
- compress  
tar -**z**cvf *xxxx.tar.gz* *directory*
- decompress  
tar -**z**xvf *xxxx.tar.gz*

### bz ###
- compress  
tar -**j**cvf *xxxx.tar.gz* *directory*
- decompress  
tar -**j**xvf *xxxx.tar.gz*

- 

