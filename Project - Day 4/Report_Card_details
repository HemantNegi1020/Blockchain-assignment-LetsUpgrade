pragma solidity ^0.4.17 < 0.6.12;

contract Report_Card_details{
    
    string public name;
    uint public roll_no;
    uint public batch;
    string public status;
    uint  Electrical;
    uint  Mechanical;
    uint  Electronics;
    uint  Computers;
    
    constructor(string newName,uint newRoll_no,uint newBatch,uint marks1,uint marks2,uint marks3,uint marks4)public{
        name = newName;
        roll_no = newRoll_no;
        batch = newBatch;
        
       }
    
    function getDetails()public view returns(string,uint,uint,string){
       
        return(name,roll_no,batch,status);
        
    } 
    
}
