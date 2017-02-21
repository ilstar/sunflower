# Sunflower (An implementation of [flower password](flowerpassword.com) with [Electron](electron.atom.io))

Where is the best place to store your password? It's nowhere!

## How it works

It uses a one-way algorithm to generate your final password in real time, by taking a 'general password' and a 'code'.

Since we don't save our password at any places, so as long as you keep your general password safe, your final passwords are secured.

Please refer to https://flowerpassword.com for more details.

## How to run the program

```
git clone git@github.com:ilstar/sunflower.git
cd sunflower
npm install
./node_modules/.bin/electron .
```

## How to package the program

1. install [electron-packager](https://github.com/electron-userland/electron-packager)
1. `electron-packager . --all`

Note: the program only be tested on Mac OS system

## Icon

<div>Icons made by <a href="http://www.freepik.com" title="Freepik">Freepik</a> from <a href="http://www.flaticon.com" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>
