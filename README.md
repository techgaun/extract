# extract
> Extract major file formats with a single command

### Installation

```shell
# linux
wget -q -O - https://raw.githubusercontent.com/techgaun/extract/master/extract >> ~/.bashrc
```

* Restart your shell session or `source ~/.bashrc`
* Note: Some of the features (eg. lzma) require tar v. 1.20+

### Usage

```shell
extract <filepath>
```

### Compressed types support

tgz, tar.gz, tbz2, tar.bz2, tar, lzma, rar

- If you come up with support for another type of compression, feel free to create PR :)
