# iterm2-zmodem
ZModem for iTerm2,rz and sz


Regular expression: rz waiting to receive.\*\*B0100<br>  
Action: Run Silent Coprocess<br>  
Parameters: /usr/local/bin/iterm2-recv-zmodem.sh<br>  

Regular expression: \*\*B00000000000000<br>  
Action: Run Silent Coprocess<br>  
Parameters: /usr/local/bin/iterm2-send-zmodem.sh<br>  


安装步骤：https://blog.csdn.net/lizz861109/article/details/104824373
