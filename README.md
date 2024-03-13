# UltimateSolidityTools


## Diagrams of Contract Interaction
- https://github.com/naddison36/sol2uml
- https://excalidraw.com/
- https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-metrics

## Linter

- Solhint
security and style guide validations for Solidity code. It helps developers to follow best practices and avoid errors in their smart contract code by analyzing it for potential issues.

Key Features of Solhint:

Customizable Rules: Developers can enable, disable, or customize rules based on their project's coding standards and preferences.
Security Checks: It includes checks for common security vulnerabilities specific to Solidity and blockchain development, such as reentrancy attacks, unchecked math, and more.
Style Guide Enforcement: Solhint can enforce consistency in coding style, adhering to the official Solidity style guide or customized style preferences.
Integration: It can be easily integrated into development environments and continuous integration pipelines, offering feedback directly in code editors or as part of the build process.
Example Usage:

After installing Solhint using npm with npm install -g solhint, you can lint a Solidity file by running:

Copy code
solhint YourContract.sol
This command will output a list of warnings and errors found in "YourContract.sol", according to the active Solhint rules.

Solhint supports configuration files (solhint.json or .solhintrc) in your project directory, allowing you to specify which rules to apply or ignore, making it a versatile tool tailored to various coding standards and practices in Solidity development.
