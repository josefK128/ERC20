truffle-ganache-metamask contracts and dApp development

required:
truffle
ganache
metamask
lite-server

install:
(1) git clone https://github.com/josefK128/ERC20.git
(2) cd into repo root
(3) npm install
(4) truffle compile
(5) launch ganache
(6) truffle migrate

(7) click metamask in Chrome
(8) choose restore from seed - used seed phrase shown in ganache
    then choose a password
(9) make certain the network is private ganache!!! (localhost:7545)
(10) npm run dev (runs lite-server)
(11) make transfers of TT tokens from account1 to account2 (for exp) 
