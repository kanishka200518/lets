Solidity feature

1. Get your own name:retrieving their registered name by address

added code:
 

 function getNameByAddress(address _addr) public view returns (string memory) {
 
        return people[_addr].name;
    }



Java feature

2. Display total registered users:retrieves how many users are currently registered

added code :

const [totalRegistered, setTotalRegistered] = useState(0);

setTotalRegistered(peopleData.length); 

console.log("Total registered users:", totalRegistered);


![FEC BLOCKBASE](https://github.com/user-attachments/assets/e85b0cec-bbd1-434e-9bfb-2156601b05be)


