# More Useful Commands

### Git


### Basic Utils
#### top
Used to view running processes on machine
```bash
top -bc -n 1 | (grep | less)
```
- `-b` flag indicates Batch mode (does not accept input, iterates `-n` number of times)
- `-n` indicates # of iterations
- `-c` toggles c state

#### systemctl (systemd)
```
systemctl | grep (daemon)
```
- grepping for particular daemons, to see their status
