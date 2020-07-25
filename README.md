# Simple-Load-Balance
Simple TCP/HTTP/HTTPS load balancer in Go

## Step 1

    apt install golang

## Step 2
Upload file to server and following command

    go build balance.go
    ./balance --bind ":1234" --balance "1.1.1.1:443" 
You can add more servers by entering commas (`,`)
**Example**

    ./balance --bind ":1234" --balance "1.1.1.1:443,2.2.2.2:443,3.3.3.3:443"

Where:
**1234** : Balances Port
**1.1.1.1** : Your Other Server IP you want to balance
**443** : Your Other Server Port
**balance.go** : Your File Name
