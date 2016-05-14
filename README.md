
Cuckoo Cycle
============
# Go implementation
This is a Go implementation of the cuckoo Proof of Work algorith "cuckoo cycle" by John Tromp.
This implementation includes the verification function as a library, and a simple multi-threaded miner.

# Installation
To install this miner just run
`go get github.com/ZiRo-/cuckgo/miner`

# Usage

```
Usage of miner:
  -e float
    	easiness in percentage (default 50)
  -m int
    	maximum number of solutions (default 8)
  -t int
    	number of miner threads (default 4)
```
# Algorithm

For details about the algorith, see: https://github.com/tromp/cuckoo
