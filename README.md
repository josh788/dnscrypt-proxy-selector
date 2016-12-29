# dnscrypt-proxy-selector
dnscrypt-proxy-selector allows you to select which dns proxy you would like to use. The script is best used in full screen as ascii text is used in the script , there is also a option to check to see if the dnscrypt-proxy is running. 

This script is designed to allow you to select from a list of over 50+ server to use.

the check option willoutput something like this:

tcp        0      0 127.0.0.1:53            0.0.0.0:*               LISTEN      9734/dnscrypt-proxy <br>
tcp        0      0 127.0.2.1:53            0.0.0.0:*               LISTEN      1/init   <br>           
udp        0      0 127.0.0.1:53            0.0.0.0:*                           9734/dnscrypt-proxy <br>
udp        0      0 127.0.2.1:53            0.0.0.0:*                           1/init              

as you can see dnscrypt-proxy is listening on port 53 for connections.<br>

Note: I did not Created Dnscrypt-proxy , i Just created This selector Program .<br>
