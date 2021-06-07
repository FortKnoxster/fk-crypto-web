[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/Naereen/badges/)
![Telegram](https://img.shields.io/badge/Join-Telegram-blue?link=https://t.me/FortKnoxster&logo=data:image/svg%2bxml;base64,PHN2ZyBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCAyNCAyNCIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjUxMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJtOS40MTcgMTUuMTgxLS4zOTcgNS41ODRjLjU2OCAwIC44MTQtLjI0NCAxLjEwOS0uNTM3bDIuNjYzLTIuNTQ1IDUuNTE4IDQuMDQxYzEuMDEyLjU2NCAxLjcyNS4yNjcgMS45OTgtLjkzMWwzLjYyMi0xNi45NzIuMDAxLS4wMDFjLjMyMS0xLjQ5Ni0uNTQxLTIuMDgxLTEuNTI3LTEuNzE0bC0yMS4yOSA4LjE1MWMtMS40NTMuNTY0LTEuNDMxIDEuMzc0LS4yNDcgMS43NDFsNS40NDMgMS42OTMgMTIuNjQzLTcuOTExYy41OTUtLjM5NCAxLjEzNi0uMTc2LjY5MS4yMTh6IiBmaWxsPSIjMDM5YmU1Ii8+PC9zdmc+)

# fkx-crypto-web
FortKnoxsters encryption algorithms used in the web app. Kryptos is a cryptographic library wrapping and implementing the Web Cryptography API. Kryptos supports symmetric keys and asymmetric key pair generation, key derivation, key wrap/unwrap, encryption, decryption, signing and verification.

## Documentation
TODO

## Getting Started

For development the recommended way is to link this package from where you are using it.

In importing project run below commands:


```
(cd ../fkx-crypto-web; npm link)
npm link fkx-crypto-web 
```

## Development
TODO

## Testing
[Debug](https://github.com/avajs/ava/blob/main/docs/recipes/debugging-with-chrome-devtools.md)


### Troubleshooting
If error similar to this:
```
mickey@minux-x1:~/Dev/fkx-web-app$ (cd ../fkx-crypto-web; npm link) && npm link fkx-crypto-web
npm ERR! path /home/mickey/Dev/fkx-crypto-web
npm ERR! code EACCES
npm ERR! errno -13
npm ERR! syscall symlink
npm ERR! Error: EACCES: permission denied, symlink '/home/mickey/Dev/fkx-crypto-web' -> '/usr/lib/node_modules/fkx-crypto-web'
npm ERR!  { Error: EACCES: permission denied, symlink '/home/mickey/Dev/fkx-crypto-web' -> '/usr/lib/node_modules/fkx-crypto-web'
npm ERR!   stack: 'Error: EACCES: permission denied, symlink \'/home/mickey/Dev/fkx-crypto-web\' -> \'/usr/lib/node_modules/fkx-crypto-web\'',
npm ERR!   errno: -13,
npm ERR!   code: 'EACCES',
npm ERR!   syscall: 'symlink',
npm ERR!   path: '/home/mickey/Dev/fkx-crypto-web',
npm ERR!   dest: '/usr/lib/node_modules/fkx-crypto-web' }
npm ERR! 
npm ERR! The operation was rejected by your operating system.
npm ERR! It is likely you do not have the permissions to access this file as the current user
npm ERR! 
npm ERR! If you believe this might be a permissions issue, please double-check the
npm ERR! permissions of the file and its containing directories, or try running
npm ERR! the command again as root/Administrator (though this is not recommended).

npm ERR! A complete log of this run can be found in:
npm ERR!     /home/mickey/.npm/_logs/2018-09-28T11_48_04_023Z-debug.log
mickey@minux-x1:~/Dev/fkx-web-app$ 
```

Then try below steps to remove any global installs (with -g):

Step 1)  
From https://github.com/creationix/nvm  
Run: wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
Open new terminal and verify installation with:
command -v nvm 

Step 2) 
nvm install stable

For linux use instead of above link commands:

(cd ../fkx-crypto-web; npm link) && npm link fkx-crypto-web 

## License

[APACHE](LICENSE)

