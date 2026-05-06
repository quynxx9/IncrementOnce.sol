# IncrementOnce.sol
IncrementOnce.sol
pragma solidity ^0.8.20;
contract IncrementOnce {
    uint public value;

    function inc() public {
        value += 1;
    }
}
