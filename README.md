# Greeting.sol
Deploy a contract on Base
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract Greeting {
    string public greeting;

    function setGreeting(string memory _g) public {
        greeting = _g;
    }
}
