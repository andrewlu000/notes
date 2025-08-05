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
