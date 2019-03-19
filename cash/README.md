# cash

This application allows you to convert money from a devise to an other one.
You can choose the devise you use, a certain amount and the devise you want to convert your amount to

## install:

❯ npm install

## launch:

❯ node bin/index.js

## Parameter:

You can choose different parameter with the following commands

❯ node bin/index.js <amount> <FROM> <TO>

<amount> to choose the amount to convert
<from> to choose the divise of your amount
<to> to chose the devise you want to convert to

when you launch the index.js you can type something like "10 usd eur pln" after, where <amount> = 10, <from> = usd and <to> = eur and pln
  
❯ node bin/index.js <amount> <FROM> <TO>

You can use the command --set -s to go back to the default curencies
for exemple if you type the command to launch index.js followed by -s <FROM> <TO> aud you will set <TO> as default curencies
❯ node bin/index.js -s <FROM> <TO>


❯ node bin/index.js --help
Will provide some informations if you need some
