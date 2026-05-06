# DoubleValue.sol
DoubleValue.sol
pragma solidity ^0.8.20;
contract DoubleValue {
    function double(uint x) public pure returns(uint) {
        return x * 2;
    }
}
