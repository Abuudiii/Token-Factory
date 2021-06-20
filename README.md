# Token-Factory
<p><b>A demo of a token factory</b></p>

<p>Follow these steps to setup the contract with the web interface:</p>

1. Setup Ganache or ganache-cli -d and change "/truffle-config.js:47" from 8545 to 7545 if needed
2. Perform "npm i", then "truffle test"
3. Creature.sol uses OpenSea - replicate to churn out another ERC721Token.sol from the factory with unique name() and symbol()
