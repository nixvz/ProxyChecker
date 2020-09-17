# ProxyChecker
A multi-threaded HTTPS proxy checker made in Go.
## Requirements
* Go (latest)

## Building
```
go build ./src/checker
```

## Setup
Put your unchecked HTTPS proxies in proxies.txt like below:
```
1.2.3.4:8080
1.2.3.4:80
1.2.3.4:443
```

## Usage
```
./checker.exe -threads=300
```
