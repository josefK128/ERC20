ERC20: contracts and dApp development 
NOTE: uses unboxed truffle contract TutorialToken.sol inheriting
openzeppelin-solidity contract StandardToken.sol
  
required:    
truffle    
ganache  
metamask  
lite-server  
  
install:  
(1) choose root directory for repo-clone - cd there
(2) git clone https://github.com/josefK128/ERC20.git    
(3) cd into public/repo root    
(4) npm install    
  
// compile/test/migrate contract 
(5) truffle compile  
(6) launch ganache  
(7) truffle migrate --reset  
  
// run dApp  
(8) npm run dev
