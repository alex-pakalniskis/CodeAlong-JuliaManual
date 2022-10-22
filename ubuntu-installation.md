# Installation
## Commands

``` bash
wget https://julialang-s3.julialang.org/bin/linux/x64/1.8/julia-1.8.2-linux-x86_64.tar.gz
tar zxvf julia-1.8.2-linux-x86_64.tar.gz
sudo ln -s /home/hackerperson/julia-1.8.2/bin/julia /usr/local/bin
```

### Download generic Linux binary
``` bash
wget https://julialang-s3.julialang.org/bin/linux/x64/1.8/julia-1.8.2-linux-x86_64.tar.gz
```

### Extract files from binary
``` bash
tar zxvf julia-1.8.2-linux-x86_64.tar.gz
```

### Create symbolic link to simplify `julia` invokation
``` bash
sudo ln -s /home/hackerperson/julia-1.8.2/bin/julia /usr/local/bin
```
* Update `/home/hackerperson/julia-1.8.2/bin/julia` to the actual location of `julia` install on your device 
