# flumipass

- A simple bash script that integrates `pass` into `fluminurs`
- `fluminurs` stores user credentials in plaintext in a file on your system
- if you are uncomfortable with that, and use a password manager like `pass` to store your passwords encrypted, this
  script is for you

## Dependencies
- [fluminurs](https://github.com/fluminurs/fluminurs) 
- [pass](https://www.passwordstore.org/) 

##Installation 
- cURL `flumipass` to `$PATH` and give it execute permissions
```
$ sudo curl -sL "https://raw.githubusercontent.com/CrimsonTitan79/flumipass/master/flumipass" -o /usr/local/bin/flumipass
$ sudo chmod +x /usr/local/bin/flumipass
```

## Usage
- The same options and arguments that are run directly using fluminurs will also work using flumipass.

```
$ flumipass --download-to ~/Documents

```


