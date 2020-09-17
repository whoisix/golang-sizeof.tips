Golang sizeof tips
==================

_Moved from [gophergala/golang-sizeof.tips](https://github.com/gophergala/golang-sizeof.tips)_

**THE PROJECT IS CLOSED. THANKS ANYONE WHO USED IT!**  

**Consider alternatives:**
- https://github.com/dominikh/go-tools/tree/master/cmd/structlayout

Web tool for interactive playing with Golang struct sizes.

Try online version ~~[here](http://47.106.211.213:7777/).~~

## Aim
Provide comfortable tool to see how fields in struct are aligned,
to compare different structs and as the result - to understand
and remember alignment rules.

## Installing
```bash
git clone github.com/gophergala/golang-sizeof.tips
cd golang-sizeof.tips
go build -o ./server
```


## Usage
```bash
./server -http=:7777 start
./server stop
./server restart
```

## Platform support
Tested on Linux and OS X x64 platforms, but should work properly and on other
*nix-like platforms.
Windows is not supported due to daemonization.

## License
[Apache License 2.0](LICENSE)
