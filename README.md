# poc-krakend


## Description

This POC  is for test dinamic(Hot reload) routes in krakend.


[![asciicast](https://asciinema.org/a/464252.svg)](https://asciinema.org/a/464252)

## Installation

```
mkdir POC
cd POC
git clone https://github.com/arturoeanton/poc-krakend.git
git clone https://github.com/arturoeanton/lura.git
git clone https://github.com/arturoeanton/gin.git

cd poc-krakend
go mod vendor
go run .

```

### Hot reload


```
touch configuration.json
```
