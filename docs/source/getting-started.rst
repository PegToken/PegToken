Getting Started
=============================================

OpenZeppelin integrates with `Truffle <https://github.com/ConsenSys/truffle/>`_, an Ethereum development environment. Please install Truffle and initialize your project with ``truffle init``::

	npm install -g truffle
	mkdir myproject && cd myproject
	truffle init

To install the PegToken library, run::

	npm init # follow instructions
	npm install PegToken

After that, you'll get all the library's contracts in the `node_modules/PegToken/contracts` folder. You can use the contracts in the library like so::

	import "PegToken/contracts/ownership/Ownable.sol";

	contract MyContract is Ownable {
	  ...
	}
