# SYNOPSIS
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/ggg.svg"><p>
This is the work repository for the Blockchain eWallet main test assesment for slate's studio implementation project.
Current development stage: CONCEPT ANALYSIS / EARLY DEVELOPMENT

<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/scw.png"><p>
# SnakeCoin eWallet with .py (python)
Part 1. 
Tiniest blockchain implementation in python assessment test for JustEd aka Aidy ed@react7.press for Slate Studio 
* http://slatestudio.com/

Original idea from:
* http://bit.ly/2AUFic6
* http://bit.ly/2AWktNu

As usual before start please pip install flask # Install our web server framework first

After running the webserver 

1. Create a transaction with curl cli below on npm:
curl "localhost:5000/txion" \
     -H "Content-Type: application/json" \
     -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'
2. Mine a new block.
curl localhost:5000/mine

# Sample output

```
$ python ~/Desktop/snakecoin.py
Block #1 has been added to the blockchain!
1  /  2019-01-03 20:28:49.257450  /  Hey! I'm block 1  /  535310e6a0
Hash: b91b140145322c765e421b5d36127627d5538be5fc29235f10040e8cdef056f5

Block #2 has been added to the blockchain!
2  /  2019-01-03 20:28:49.257495  /  Hey! I'm block 2  /  b91b140145
Hash: 4003bf32fee520dd4590cf61872c74cdf05ae93e0957fea7f79ed7dddb58e1d6

Block #3 has been added to the blockchain!
3  /  2019-01-03 20:28:49.257515  /  Hey! I'm block 3  /  4003bf32fe
Hash: 6119367e51e2ed1015d5c86bcf2c2671351ac5d4ad188703f015bb49ec8783b4
```

---
# Blockchain eWallet with React-Native/ Redux and NodeJs
Part 2.
## My version eWallet Blockchain React-Native / Redux App
---
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/welcome.png"><p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Screen%20Shot%202019-01-04%20at%202.07.42%20PM.png"><br>
The Homescreen<p>

## The Sourcecode
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Configjs.png"><br>
~/common/Config.js<p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Layoutjs.png"><br>
~/common/Layout.js<p> 
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Constantjs.png"><br>
~/common/Constant.js<p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Languagejs.png"><br>
~/common/Language.js<p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Indexjs.png"><br>
~/common/Index.js<p>

<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Screen%20Shot%202019-01-03%20at%207.46.11%20PM.png"><p>

---
# Blockchain eWallet with React-Native/ Redux and NodeJs
Part 2.
## My version eWallet Blockchain React-Native / Redux App

<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/scw.png"><br>
Splash Screen.<p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Screen%20Shot%202019-01-04%20at%202.07.42%20PM.png"><br>

## The wallet extensions
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/blockchain-test.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/wallet-altcoin.png"><br>
Default credit value are be set to $5.00<br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Screen%20Shot%202019-01-12%20at%201.07.19%20PM.png"><br>
eWallet backend interface for admin to transfer amount to others users.<br>

## The Sourcecode
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Configjs.png"><br>
~/common/Config.js<p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Layoutjs.png"><br>
~/common/Layout.js<p> 
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Constantjs.png"><br>
~/common/Constant.js<p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Languagejs.png"><br>
~/common/Language.js<p>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/Indexjs.png"><br>
~/common/Index.js<p>

## Android Screenshots with Expo
---
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/a.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/b.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/c.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/d.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/e.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/f.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/g.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/h.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/i.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/j.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/k.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/l.png"><br>
<img src="https://github.com/React7Tech/slatestudio-assessment/blob/master/m.png"><br>
... 

This project some part was generated with [electron, vue, yarn, and expo]
But i'm sorry--- you may view my /src via bitbucket due github not permit my repo to be private. (Free Version! and i don't trust github)
BitBucket Url: https://bitbucket.org/react7store/snakecoin-wallet-rn-redux/src
or you may clone that first in advanced ~ $ git clone https://react7store@bitbucket.org/react7store/snakecoin-wallet-rn-redux.git
or
Expo Documentation:
https://expo.io/@react7press/slatestudio-mhubvendor<br>
After it reload inside your device login with below details or you may create new account.<br>
The FB login is not ready for this app yet.<p>
Username: demo<br>
Password: 1234<p>

Owh btw my team organisation i.d with Docker Hub is react7store.

Warmest regards..
JustEd aka R. Aidy
