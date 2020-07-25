# Simple-Load-Balance
Simple TCP/HTTP/HTTPS load balancer in Go

## Step 1
apt install golang
## Step 2
Upload file to the server and then click the following command
' go build main.go ' ( main.go = Your File Name)
## Step 3
./main --bind ":1234" --balance "1.1.1.1:443,2.2.2.2:443" 

./Filename! 
You can add more servers by entering commas (,)
