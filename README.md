# manual-wireshark


Ctrl + R : 화면 

### 필터링
not arp     
ip.addr == 40.77.226.13 and not arp  
ip.addr == 27.0.236.201 and not arp and tcp  
ip.addr == 210.103.251.39 and not arp and not icmp and not tcp.port == 60794  

// 
ip.addr == 27.0.236.68


### 포트 보는법
statistics - > conversations -> tcp -> limit to display filter  
