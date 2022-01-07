# flumi-pass

- A simple bash script that integrates `pass` into `fluminurs`
- `fluminurs` stores user credentials in plaintext in a file on your system
- if you are uncomfortable with that, and use a password manager like `pass` to store your passwords, this
  script is for you

## Dependencies
- [fluminurs](https://github.com/fluminurs/fluminurs) 
- [pass](https://www.passwordstore.org/) 


# #Installation 
- cURL flumi-pass to $PATH and give it execute permissions
'''
$ sudo curl -sL "https://raw.githubusercontent.com/CrimsonTitan79/flumi-pass/master/flumi-pass" -o /usr/local/bin/flumi-pass
$ sudo chmod +x /usr/local/bin/flumi-pass
'''


## Usage
- The same options and arguments that are run directly using fluminurs will also work using flumi-pass.

```
$ flumipass --download-to ~/Documents

```


