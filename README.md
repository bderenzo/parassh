# parassh

Minimal parallel SSH program written in shell

## Install

To install, run: `sudo cp parassh /usr/local/bin/`

## Usage

Example:
```
$ parassh -o '-p 2222' server{1..3} -- date +%s.%N
server3
1592336502.136820026
server1
1592336502.179848294
server2
1592336502.199682719

Total: 3 hosts(s), 1 second(s)
```

## Help 

To view help, run: `parassh -h`
