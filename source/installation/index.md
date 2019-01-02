## Binary Distribution
Download the latest binary from [Release Page](https://github.com/isacikgoz/tldr/releases) then; decompress the file and copy the executable somewhere in your `$PATH`

**for instance** :

### macOS (darwin)
```bash
curl -OL https://github.com/isacikgoz/tldr/releases/download/v0.5.0/tldr_0.5.0_darwin_amd64.tar.gz  
tar -xzf tldr_0.5.0_darwin_amd64.tar.gz  
```

### Linux
```bash
curl -OL https://github.com/isacikgoz/tldr/releases/download/v0.5.0/tldr_0.5.0_linux_amd64.tar.gz
tar xzf tldr_0.5.0_linux_amd64.tar.gz
```

### After that please put executable to your `PATH`:
*`chmod +x tldr` if necessary
```bash
sudo mv tldr /usr/local/bin
```

## Source Build
Source build requires golang compiler and minimum golang 1.10 is recommended.
- If you don't have golang installed refer to [golang.org](https://golang.org/dl/).
- You should have $GOPATH env variable set and your $PATH should include $GOPATH/bin to run app from anywhere.

To install run the following command;
```bash
go get -u github.com/isacikgoz/tldr
```

p.s. I prefer using gopath like this in my zshrc or bashrc;
```bash
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
```

## Use
Run `tldr` from anywhere you want.