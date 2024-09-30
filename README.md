# pwnshodo
Automatic tool to find subdomains using shodan premium api.

### Install
```
$ go install github.com/pwnosec/pwnshodo@latest
$ go build .
$ mv /usr/local/bin/
$ pwnshodo

# verify inside your $GOPATH the folder "bin"
```
### Usage
```
go run main.go -d target.com -s YourAPIKEY / go run main.go -f file -s YourAPIKEY
pwnshodo -d target.com -s MYShodaNKey [-f input_file]
```

![](https://i.ibb.co.com/23v2gY0/Screenshot-2024-10-01-at-01-06-57.png)
