#**[fd]**
---
##Knowledge
###Linux file descriptor
0 stdin
1 stdout
2 stderr
###c function
ssize_t read(int fd,void *buf,size_t nbyte) 

int system(const char *string)

##Solution 
Let the value of argv[1] equal 0x1234(4460),the fd equals 0.The program then reads from stdin.Input "LETMEWIN",get the flag through system call.