ERC20: contracts and dApp development 
NOTE: uses unboxed truffle contract TutorialToken.sol inheriting
openzeppelin-solidity contract StandardToken.sol
  
required:    
truffle    
ganache  
metamask  
lite-server  
  
install:  
(1) git clone https://github.com/josefK128/truffle-ganache-metamask.git    
(2) cd into repo root    
(3) npm install    
  
// compile/test/migrate contract (optional - else jump to (7))  
(4) truffle compile  
(5) launch ganache  
(6) truffle migrate --reset  
  
// simply run dApp   
(7) launch ganache (not needed if steps 4,5,6,7 were done)  
(8) click metamask in Chrome  
(9a) enter password  OR  
(9b) choose restore from seed - used seed phrase shown in ganache  
    then choose a password  
(10) make certain the network is private ganache!!! (localhost:7545)  
(11) npm run dev (runs lite-server) => dApp launches in browser window  
(12) choose dog - click adopt - should change to 'success' - may need to  
     refresh browser  
