# FF-fix

While I was in webpage which wanted to use my camera and mic, <br>
my camera picture was upside down. <br>
<br>
Here is quick fix, which was working for me. <br>

```
#/bin/sh
export LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libv4l/v4l1compat.so
firefox 
```
<br>
And remember change your file as execute, <br>
``` chmod +x <filename>  ```


