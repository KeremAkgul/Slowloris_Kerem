
# SlowLorisAttack_pyhon
this script create several tcp-sessions(with multiple threads) and send HTTP-POST request to the target machine

+ RUN:
    + python ./driver.py
    
#Added By Kerem
    uri argument changed to Free_Test_Data_10.5MB_PDF.pdf. You can change this in driver.py with vim editor.
    
    
+ About ./driver.py Code Variables:
    + target :  target IP address
    + port:     target port number
    + connection_count: how many connections do you want this script to create and then send GET requests
    + timeInterval: at which time interval do you want this script to send GET requests
    + uri: specify the uri you want to request for
        + note that: when you want to specify the uri, you should not put '/' character at first of your string
