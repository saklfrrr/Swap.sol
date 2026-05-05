# Swap.sol
Swap.sol
pragma solidity ^0.8.20;
contract Swap {
    function swap(uint a, uint b) public pure returns(uint, uint) {
        return (b, a);
    }
}
