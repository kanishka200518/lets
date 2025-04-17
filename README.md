Solidity feature
1. Get your own name:retrieving their registered name by address
added code:
 
 function getNameByAddress(address _addr) public view returns (string memory) {
        return people[_addr].name;
    }
