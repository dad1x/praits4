# praits4
opanvas init
## install openvas 

´´´
nmap -sP 192.168.178.1/24 | awk '/is up/ {print up}; {gsub (/\(|\)/,""); up = $NF}'
´´´
