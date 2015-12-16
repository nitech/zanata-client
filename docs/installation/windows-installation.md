1. Click [here](http://0install.de/files/zero-install.exe) to download and install [0Install for Windows](http://0install.net/install-windows.html).
2. Run `0install https://raw.githubusercontent.com/zanata/zanata.github.io/master/files/0install/zanata-cli-jre.xml` to setup alias.
3. Now you can run `zanata-cli --help` for more options.

*Note: If you have installed `zanata-cli` previously through another method, you need to uninstall that for this to work.*



### Useful command

**Run Zanata-cli without alias**
```
0launch https://raw.githubusercontent.com/zanata/zanata.github.io/master/files/0install/zanata-cli-jre.xml {command}
```

**Update Zanata-cli manually**
```
0install update https://raw.githubusercontent.com/zanata/zanata.github.io/master/files/0install/zanata-cli-jre.xml
```

**Zanata-cli feed without JRE dependency**

`https://raw.githubusercontent.com/zanata/zanata.github.io/master/files/0install/zanata-cli.xml`
