# UnRAR
UnRAR is a free utility for RAR archives. It is useful to uncompress rar files through command line in terminal, i.e in headless OS or any system have not display or it is disabled for some reason. There is some last stable or beta ARM/Linux compilations from official unrar source here. Source code got from https://github.com/pmachapman/unrar

## How to compile your own

When you get your source version from unrar, you only need to execute:
```
make -f makefile
install -v -m755 unrar /usr/bin
```
## License

It applies license found in https://github.com/pmachapman/unrar/blob/master/license.txt